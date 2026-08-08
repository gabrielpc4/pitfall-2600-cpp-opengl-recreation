# PITFALL2600

PITFALL2600 is an independent C++ and OpenGL game project inspired by **Pitfall!**, the classic Activision platform game designed by David Crane for the Atari 2600 in 1982.

The original game challenged the player to guide Pitfall Harry through a jungle, collect treasures, and survive hazards within a limited time. This project recreates that style of adventure as a desktop game, expanding the core ideas with animated sprites, climbing, swinging, configurable scenarios, and a broader set of hazards.

This repository is an independent implementation for learning and experimentation. It is not the original Pitfall! game, an Atari 2600 ROM, or an official Activision product. [The classic reference is documented here](https://atari.fandom.com/wiki/Pitfall%21_%282600%29).

## Gameplay

- Explore connected jungle scenarios.
- Collect treasure such as money bags, silver bars, gold bars, and diamond rings.
- Jump over holes and obstacles.
- Climb ladders and use underground tunnels.
- Swing from vines to cross dangerous sections.
- Avoid rolling logs, crocodiles, snakes, scorpions, bonfires, water, and black holes.
- Manage lives and restart after defeat.
- Track score and progress through generated scenarios.

## Controls

| Key | Action |
| --- | --- |
| Left Arrow | Move left or climb out to the left |
| Right Arrow | Move right or climb out to the right |
| Up Arrow | Jump or climb up a ladder |
| Down Arrow | Climb down a ladder |
| Space | Start, jump, release a vine, climb out, or restart after game over |

## Technology

- C++
- OpenGL
- GLUT-style windowing and input
- Visual Studio solution and project files
- Sprite, animation, collision, world, and scenario systems written in C++

## Project structure

- `PITFALL2600.sln`: Visual Studio solution.
- `PITFALL2600/`: C++ game source and project files.
- `PITFALL2600/PitfallGame.cpp`: Main game state, update loop, drawing, collisions, input, and scoring.
- `PITFALL2600/Player*`: Player movement, animation, jumping, climbing, falling, and vine interactions.
- `PITFALL2600/World.*`: World elements, treasures, hazards, and scenario state.
- `PITFALL2600/Scenario*.txt`: Configurable world elements and enemy layouts.
- `GameProjectLog.txt`: Development notes documenting the game's implementation history.

## Building on Windows

1. Install Visual Studio with the C++ desktop development workload.
2. Open `PITFALL2600.sln`.
3. Select the desired configuration and platform.
4. Build the solution.
5. Run the `PITFALL2600` project.

The project uses OpenGL and GLUT-style APIs and may require compatible legacy dependencies or small configuration adjustments on modern Visual Studio installations.

## License

This project is licensed under the [MIT License](LICENSE).

