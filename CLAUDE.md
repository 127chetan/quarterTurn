# Quarter Turn — Project Context

## What this game is
A 2.5D pixelated puzzle platformer built in **Godot 4**. Each level is set inside a person's dream. When the dreamer shifts in their sleep, the level rotates 90 degrees — changing the direction of gravity and transforming the puzzle state.

## Core mechanic
- The **level rotates** 90 degrees (a "quarter turn")
- **Gravity changes** direction with the rotation
- The **character does not rotate** — they adapt to the new gravity and land on whatever is now the floor
- **No phone rotation required** — the rotation is purely visual within the screen

## Puzzle mechanics
- Block pushing (Sokoban-style)
- Pathfinding puzzles

## Rotation triggers (varies by stage)
- **Timed** — rotation happens automatically after a set interval
- **Player-controlled** — player decides when to rotate

## Block behavior on rotation
Blocks briefly stay in place (~0.5–1 second), then fall in the new gravity direction.
Implemented by temporarily setting blocks to static, then switching back to dynamic after a short timer.

## Art style
Pixel art, 2.5D (parallax layers for depth)

## Platform
iOS (Godot 4 → export to iOS)

## How we're working
- Starting very small, iterating and building together
- Learning Godot fundamentals along the way — explain concepts as we go
- User is new to Godot and game development

## Name
**Quarter Turn** (working title — name describes the core mechanic)

## What's next
1. Install Godot 4 (standard, not .NET) from godotengine.org
2. Create the Godot project inside the cloned repo folder
3. Build Stage 1: a character that can move and jump in a basic scene
