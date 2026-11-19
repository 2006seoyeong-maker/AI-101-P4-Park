# Testing and Failure Log — Dead Road

## 1. Testing Overview

**Project:** AI 101 Project 4 — Vibe Coding

**Game:** Physics Ball / Dead Road: Ricochet Evolution V5

**AI Tool:** ChatGPT

**Development Tools:** Visual Studio Code, GitHub, Google Chrome / Microsoft Edge

**Purpose:** Test the original game, compare it with the revised version, and document the design changes and remaining limitations.

## 2. Cycle 1 and Cycle 2 Test Results

| Test | Expected Result | Cycle 1 | Cycle 2 | Comparison |
|---|---|---|---|---|
| Test 1: Game Launch | Game opens in a browser | Pass | Pass | Unchanged |
| Test 2: Ball Launch | Space launches the ball | Pass | Pass | Unchanged |
| Test 3: Movement | Movement controls respond | Pass | Pass | Unchanged |
| Test 4: Restart | R restarts the game | Pass | Pass | Unchanged |

The four basic functionality tests passed in both versions, based on my gameplay checks.

These results show that the original controls remained functional after the revision.

## 3. Main Design Limitation

The original Physics Ball game was a short physics puzzle where the player launched a ball toward a target platform.

Although the basic controls worked, I felt that the game was too simple and had limited replay value.

The main limitation was not a technical failure. It was a gameplay design issue that I identified while reviewing the first version.

I wanted to make the game more engaging, challenging, and replayable.

## 4. Design Revision — Cycle 2

**Related Decision:** ADR-003 — Endless Zombie Survival

I decided to change the game from a short physics puzzle into an endless zombie survival experience.

The revised version introduced:

- Continuous forward movement.
- Approaching zombie enemies.
- Collision-based combat.
- Road obstacles.
- Survival energy and scoring.
- Longer gameplay without a fixed finish line.

**Result:**

The revised game introduced new survival mechanics while retaining the basic movement and restart functions.

However, the four original functional tests did not directly measure whether the gameplay became more enjoyable.

## 5. Cycle 2 Evaluation

The same four basic tests were used to compare the original and revised versions.

All four recorded results remained unchanged because the basic functions worked in both versions.

This comparison shows that the revision retained the tested controls, but it does not prove that every new gameplay mechanic worked correctly.

Additional gameplay testing would be necessary to evaluate difficulty, replayability, and player satisfaction.

## 6. Additional Development — Versions 3 to 5

**Related Decision:** ADR-004 — Gameplay Expansion and Visual Improvements

After Cycle 2, I continued developing the game to improve its gameplay variety and visual feedback.

The later versions introduced:

- WASD movement controls.
- Shift speed boost.
- Ten different zombie types.
- Changing environments and road obstacles.
- Collectible items and power-ups.
- Ball appearance changes based on upgrades.
- Ricochet Rampage, a special skill that bounces between enemies and obstacles.
- Skill cooldowns.
- Stronger collision effects, particles, and score animations.
- A Prism Core system that grants temporary invincibility after collecting seven cores.

The final selected version is Dead

