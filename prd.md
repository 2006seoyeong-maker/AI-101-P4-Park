# Dead Road: Ricochet Evolution V5 — Product Requirements Document

## 1. Goal

Create a browser-based endless zombie survival game where the player controls a rolling ball, defeats enemies through collisions, avoids dangerous obstacles, collects power-ups, and survives as long as possible.

The game should combine physics-inspired movement, fast-paced combat, evolving environments, and satisfying visual feedback.

## 2. Target User

College students and casual gamers who enjoy arcade action, survival challenges, and games with upgrades and special abilities.

The player should feel excitement, speed, and a sense of progression during gameplay.

## 3. Core Features

### Feature 1: Movement and Survival

- The user can hold and release Space to launch the ball.
- The ball continues moving forward after launch.
- The user can steer with A and D.
- W and S adjust movement speed.
- Holding Shift activates a temporary speed boost.
- The player must avoid obstacles and manage survival energy.
- The game ends when survival energy reaches zero.
- The user can restart with R.

### Feature 2: Combat and Special Abilities

- Zombies continuously appear along the road.
- The game includes ten different enemy or character types.
- The player can defeat hostile zombies by colliding with them.
- Certain protected targets must not be attacked.
- Destroying enemies increases the score and kill count.
- Successful attacks display impact effects, particles, score pop-ups, and combo feedback.
- Pressing Q activates Ricochet Rampage.
- Ricochet Rampage makes the ball bounce between nearby enemies and obstacles, destroying valid targets.
- The skill has a cooldown to prevent continuous use.

### Feature 3: Items, Upgrades, and Progression

- The user can collect items that provide temporary benefits.
- Power-ups can improve speed, protection, combat abilities, or scoring.
- The ball begins with a neutral metallic appearance.
- Its appearance changes when upgrades or special effects are active.
- Collecting seven Prism Cores activates temporary invincibility.
- The road contains changing environments, terrain, and obstacles.
- The game tracks survival progress through distance, kills, score, and combos.

## 4. Gameplay Flow

1. The player starts with a neutral-colored ball.
2. The player charges and launches the ball using Space.
3. The ball moves continuously along the road.
4. The player steers using WASD and accelerates with Shift.
5. Zombies, obstacles, and collectible items appear during gameplay.
6. The player destroys hostile enemies while avoiding protected targets.
7. Collecting items temporarily improves the ball's abilities.
8. The player can activate Ricochet Rampage when its cooldown is complete.
9. Collecting seven Prism Cores grants temporary invincibility.
10. The game continues until the player's survival energy reaches zero.
11. The player can restart and attempt to achieve a higher score.

## 5. Look and Feel

- Stylized 2.5D graphics with a sense of depth.
- Third-person camera following the rolling ball.
- Dark, post-apocalyptic road environments.
- Different zombie appearances and behaviors.
- Changing environmental scenery and road obstacles.
- A neutral metallic ball that evolves visually through power-ups.
- Bright particle effects, impact animations, and motion trails.
- Screen shake and visual feedback during powerful collisions.
- Large score pop-ups and visible combo indicators.
- A clear HUD showing survival energy, score, kills, distance, and ability status.

## 6. Controls

| Key | Function |
|---|---|
| Space | Charge and launch the ball |
| W / S | Adjust speed |
| A / D | Steer left and right |
| Shift | Activate speed boost |
| Q | Activate Ricochet Rampage |
| R | Restart |
| P | Pause |
| M | Toggle sound |

## 7. Out of Scope

- Online multiplayer.
- Online accounts or authentication.
- Global leaderboards.
- Photorealistic 3D graphics.
- Advanced realistic physics simulation.
- Online save synchronization.
- AI-controlled cooperative players.

## 8. Success Criteria — Done When

**Check 1: Basic Gameplay**

The game opens directly from `build/index.html`. The player can launch the ball, steer using WASD, activate Shift boost, and restart the game.

**Check 2: Combat and Survival**

Hostile zombies and obstacles appear during gameplay. Collisions affect the game state, scores update correctly, and survival energy determines when the game ends.

**Check 3: Special Abilities and Progression**

Ricochet Rampage activates with Q, targets valid enemies and obstacles, and respects its cooldown. Collecting seven Prism Cores activates temporary invincibility, and upgrades visibly affect the ball.

## 9. Development History

**Cycle 1:** Created a simple physics puzzle game focused on launching a ball toward a target.

**Cycle 2:** Changed the game into an endless zombie survival experience, adding continuous movement, enemies, obstacles, and survival energy.

**Additional Versions 3–5:** Expanded combat, movement controls, item collection, visual effects, special abilities, and ball customization.

Major design changes are documented in the `decisions/` folder.

## 10. Known Limitations

- The game uses stylized 2.5D graphics rather than full 3D rendering.
- Physics and collisions are simplified.
- Visual effects may reduce performance on lower-powered devices.
- Game balance may require further adjustment.
- Not all V5 mechanics have been fully verified through documented gameplay tests.
