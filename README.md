# 3D Marble Puzzle Game

**3D Marble Puzzle Game** is a small third-person physics-based maze and puzzle game developed in Unreal Engine.

The project is a remake and modernization of the original Unity project:

`Nilsson82/3d-Puzzle-Game`

Instead of controlling a Rubik's Cube, the player controls a **marble ball** and travels through a series of small maze-like levels.

The objective is simple:

**Navigate the maze, collect the gold coins, find the exit, and achieve the best possible score.**

Each level is designed to be relatively small and replayable, with multiple possible routes and different ways to reach the goal.

## Gameplay

The player controls a rolling marble through compact 3D levels containing:

* Mazes
* Platforms
* Ramps
* Bridges
* Moving obstacles
* Traps
* Jumps
* Hidden paths
* Shortcuts
* Gold coins
* Level exits

The marble uses physics-based movement, making momentum and careful control important parts of the gameplay.

## Gold Coins

Gold coins are placed throughout each level.

Players can choose between:

* Taking a fast route to the finish
* Exploring the level to collect more coins
* Finding hidden coins
* Taking more difficult shortcuts
* Trying to complete the level with every coin collected

This creates different ways to play the same level.

## Scoring

Each level has its own score.

The score can be based on:

* Gold coins collected
* Completion time
* Number of deaths or restarts
* Optional hidden collectibles
* Bonus objectives

Example:

```text
Coins collected:      850
Time bonus:           420
No-death bonus:       250
Hidden coin bonus:    100
-------------------------
Final Score:        1,620
```

## Level Scoreboard

Every level should have its own scoreboard.

The scoreboard can show:

```text
Rank
Player Name
Score
Completion Time
Coins Collected
```

Example:

```text
1. Anders       8,450    01:32.48    24/24
2. Ester        8,120    01:38.20    24/24
3. Player03     7,950    01:28.11    21/24
```

A local scoreboard should be implemented first.

Online leaderboards can be added later.

## Level Structure

The game should use many small levels rather than one large open world.



Each world can introduce new mechanics.

## Environments

Levels can have different visual themes:

* Grasslands
* Viking ruins
* Castles
* Caves
* Snow and ice
* Desert
* Jungle
* Lava and volcanoes
* Ancient temples
* Space or abstract bonus levels

## Difficulty

Early levels should teach movement and basic mechanics.

Later levels can introduce:

* Narrow platforms
* Faster moving obstacles
* Falling platforms
* Ice
* Wind
* Water
* Moving walls
* Rotating platforms
* Teleporters
* Timed gates
* Switch puzzles
* Dangerous shortcuts

## Replayability

Levels should encourage replaying them.

Players can try to:

* Beat their previous score
* Beat their fastest time
* Collect every coin
* Discover shortcuts
* Find hidden areas
* Complete bonus objectives
* Reach the top of the scoreboard

## Main Menu

The game should start with a simple menu:

```text
PLAY

LEVEL SELECT

SCOREBOARDS

SETTINGS

CREDITS

QUIT
```

## Level Select

Each level can display:

```text
Best Score
Best Time
Coins Found
Total Coins
Completion Status
```

Example:

```text
LEVEL 1-3

Best Score: 4,850
Best Time: 01:44.20
Coins: 18 / 20

[ PLAY ]
```

## Core Game Loop

```text
Select Level
      ↓
Start Level
      ↓
Navigate Maze
      ↓
Collect Gold Coins
      ↓
Discover Shortcuts
      ↓
Reach Exit
      ↓
Calculate Score
      ↓
Update Scoreboard
      ↓
Replay or Select Next Level
```

## Development Goal

The project should remain deliberately simple.

The first playable version only needs:

* One marble
* Physics-based movement
* Camera
* One small maze
* Gold coins
* Level timer
* Finish area
* Score calculation
* Local high-score table
* Restart button
* Main menu

Once these systems work correctly, additional levels and mechanics can be added.

## Engine

Unreal Engine 5.8

## Genre

* 3D Puzzle
* Maze
* Physics
* Platformer
* Casual
* Score Attack
