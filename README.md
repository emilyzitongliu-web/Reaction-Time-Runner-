# Reaction-Time-Runner-
2D reaction-training game built in Godot 4. Features randomised obstacles and combo-based enemy encounters

Reflex Runner is a 2D infinite runner designed to train, test, and track the player’s reaction speed over time.  
The game blends mechanics from *Temple Run*, *Geometry Dash*, and traditional reaction-time tests, offering a far more engaging and data-driven way to measure performance.

This project is being developed as part of the OCR A-Level Computer Science NEA.

---

## Features

### Reaction-Time Training
- Automatically logs the timestamp of every obstacle spawn.
- Records the player’s reaction time for each successful dodge.

### Combo-Based Enemy Encounters (Adventure Mode)
- Enemies spawn with a random 3-key arrow-combo (DDR-style).
- Players must input the sequence correctly to defeat them.
- Visual feedback: correct inputs turn green, errors flash red.
- Failure or mistimed input triggers an immediate game reset.

### Randomised Obstacles
- Obstacles spawn ahead of the player using variable intervals.
- All objects move with the world to maintain infinite-runner flow.
- Reaction window adjusts automatically with difficulty.
---

**GDScript**
- Scene-based architecture with:
  - `Player`
  - `Obstacle`
  - `Enemy`
  - `Spawner` (handles dynamic generation)
  - Mode managers (`NormalMode`, `AdventureMode`)



