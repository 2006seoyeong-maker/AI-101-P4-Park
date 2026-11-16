# Testing and Failure Log — Dead Road

## 1. Testing Overview

**Project:** AI 101 Project 4 — Vibe Coding

**Game:** Physics Ball / Dead Road

**Purpose:** Compare the original game with the revised version using the same four tests.

## 2. Cycle 1 and Cycle 2 Test Results

| Test | Expected Result | Cycle 1 | Cycle 2 | Comparison |
|---|---|---|---|---|
| Test 1: Game Launch | Game opens in a browser | Pass | Pass | Unchanged |
| Test 2: Ball Launch | Space launches the ball | Pass | Pass | Unchanged |
| Test 3: Movement | Movement controls respond | Pass | Pass | Unchanged |
| Test 4: Restart | R restarts the game | Pass | Pass | Unchanged |

These results summarize the basic functional checks. Each pass should be supported by its corresponding test evidence.

## 3. Main Design Limitation

The original Physics Ball game had a short course and limited replay value.

I decided to change the gameplay into an endless survival experience with zombies, obstacles, and scoring.

This was a design decision based on my evaluation of the game, rather than a failure identified by the four functional tests.

## 4. Design Revision

**Related Decision:** ADR-003

The revised game introduced:
- Continuous forward movement.
- Approaching zombies.
- Collision-based attacks.
- Road obstacles.
- Survival energy and scoring.

## 5. Cycle 2 Evaluation

The revised game retained the basic controls and introduced additional gameplay systems.

The four functional tests did not demonstrate an improvement because the tested functions worked in both versions.

Further gameplay testing would be needed to evaluate whether the new survival mechanics improved the overall experience.

## 6. Additional Development — V3 to V5

Later versions introduced:
- WASD controls and Shift boost.
- Ten zombie types.
- Power-ups and changing ball designs.
- Ricochet Rampage combat skill.
- Seven Prism Core collectibles for temporary invincibility.

These features require separate testing and should not be considered verified by the original Cycle 1 and Cycle 2 tests.

## 7. Known Limitations

- Simplified physics and 2.5D graphics.
- Gameplay balance needs additional testing.
- Visual effects may affect performance.
- The latest V5 features are not fully verified.

## 8. Evidence

Screenshots should be stored in `build-record/tests/`.

Each screenshot should identify the test, game version, and actual result.

Only tests that were actually performed should be marked as passed.
