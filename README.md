# Buzz Bombers — Programming Fundamentals

Semester project for the **Programming Fundamentals (PF)** course: a remake of the classic *Buzz Bombers* arcade game in **C++ with SFML** — shoot down waves of bees before they build honeycomb across the screen.

## Repository status

> ⚠️ The current files (`proj2`, `Music`, `Textures`, `arial`) are **empty placeholders** — the full source, audio, textures, and font were not uploaded with this commit. The structure below reflects the intended layout.

| Entry | Intended content |
|---|---|
| `proj2` | Main C++/SFML game source |
| `Textures` | Sprite sheets (bees, hive, spray can, honeycomb) |
| `Music` | Background music and sound effects |
| `arial` | Font used for the HUD/score |

## The game (as built for the course)

- Player-controlled spray can moving along the bottom of the screen
- Waves of worker and soldier bees that convert to honeycomb blocks when they land
- Score, levels, and increasing difficulty
- Built with **procedural C++** (arrays, loops, functions — no OOP), per PF course constraints, rendered with **SFML**

## Building (once source is restored)

```bash
g++ proj2.cpp -o buzz-bombers -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./buzz-bombers
```
