# Physics Ball — Product Requirements Document

## 1. Goal
Create a simple 3D-style physics puzzle game where players launch a ball and use gravity, momentum, and directional control to reach a target platform.

## 2. User
A college student who enjoys interactive physics challenges.

## 3. Core Features

### Feature 1: Ball Launching
- The user can hold Space to charge launching power.
- A power meter shows the charging level.
- Releasing Space launches the ball.
- Higher power creates greater initial speed.

### Feature 2: Physics-Based Movement
- The user can use arrow keys to influence the ball's movement.
- Left and Right apply sideways forces.
- Up applies a small forward force.
- Down reduces forward speed.
- Gravity, momentum, and friction affect movement.
- A third-person camera follows the ball from behind.

### Feature 3: Mission and Restart
- The user can navigate a ramp and jump across a gap.
- Landing on the target platform completes the mission.
- Falling off the course results in failure.
- Pressing R restarts the level.

## 4. What Happens
1. The ball starts at the beginning of the course.
2. The player holds Space to charge power.
3. Releasing Space launches the ball forward.
4. The ball moves across the course using simplified physics.
5. The player adjusts its direction using arrow keys.
6. Reaching the target platform results in victory.
7. Falling off the course results in failure.

## 5. Look and Feel
- A simple 3D-style environment.
- A third-person camera following closely behind the ball.
- The ball appears near the bottom center of the screen.
- Clean platforms, ramps, and obstacles.
- A visible launching power meter.
- Smooth animations and clear visual feedback.

## 6. Out of Scope
- Multiplayer gameplay.
- Multiple levels in the first version.
- Advanced realistic physics.
- Online accounts and leaderboards.
- AI-controlled opponents.
- Complex character customization.

## 7. Done When

1. The game opens in a browser from build/index.html and displays the ball, course, and power meter.

2. Holding and releasing Space launches the ball with variable power, and arrow keys affect its movement while preserving momentum.

3. The game detects victory and failure correctly, and pressing R restarts the game.
## Cycle 2: Zombie Survival Update

### Reason for Change
The original Physics Ball game was too short and simple for the intended experience. I decided to explore a continuous survival game instead of a short physics puzzle.

### Updated Goal
Create an endless zombie survival game where the player controls a continuously moving ball, defeats approaching zombies through collisions, and avoids road obstacles.

### Updated Features
1. The ball continues moving forward after the initial launch.
2. Zombies continuously appear and approach the player.
3. The player defeats zombies by colliding with them.
4. Obstacles appear on the road and reduce survival energy when hit.
5. Defeating zombies restores survival energy.
6. The game tracks kills, distance, and survival status.

### Updated Success Criteria
1. The game runs continuously after the initial launch without requiring another launch.
2. Zombie collisions increase the kill count and restore survival energy.
3. Obstacle collisions reduce survival energy, and the game ends when energy reaches zero.

### Scope Change
The original target-platform goal is replaced by endless survival. This is a new design direction, not a fix supported by a documented Cycle 1 failure.