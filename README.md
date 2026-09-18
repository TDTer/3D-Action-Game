# 3D-Action-Game

A 3D game prototype built with **Unreal Engine 5.6**, focused on learning and experimenting with gameplay using **Blueprints**. The project currently includes a playable character, enemies, attack and health systems, interactive actors, and prototype gameplay content.

## Technologies

- Unreal Engine `5.6`
- Blueprint Visual Scripting
- Enhanced Input
- Modeling Tools Editor Mode
- AutoSizeComments plugin
- Paragon Crunch character assets, animations, audio, and effects
- Unreal Engine Starter Content

## Current Features

- Third-person character controls.
- Character movement, camera rotation, and jumping.
- Player and enemy characters with Blueprint-based AI behavior.
- Combo attack system.
- Animation Montage integration for attack sequences.
- Hand-based hit tracing for melee combat detection.
- Attack and health components.
- Prototype actors such as doors, jump pads, wobble targets, trace actors, and sound actors.
- Character animations, materials, sound effects, and VFX for Crunch.
- Prototype gameplay and interaction content.

## Controls

| Action | Keyboard / Device |
|---|---|
| Move forward/backward | `W` / `S` or left gamepad stick |
| Move left/right | `A` / `D` or left gamepad stick |
| Turn camera horizontally | Mouse or right gamepad stick |
| Look up/down | Mouse or right gamepad stick |
| Jump | `Space Bar` or bottom face button on a gamepad |

## Main Project Structure

```text
FristProject/
├── Config/
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   └── DefaultInput.ini
├── Content/
│   ├── AI/                 # AI controllers
│   ├── Bluprints/          # Main gameplay Blueprints
│   ├── Components/         # Attack and health components
│   ├── Controllers/        # Player controllers
│   ├── LevelPrototyping/   # Interactive actors and prototype content
│   ├── ParagonCrunch/      # Crunch character, animation, audio, and VFX assets
│   ├── StarterContent/     # Unreal Engine sample content
│   └── ThirdPerson/        # Third-person sample content
└── FristProject.uproject
```

## Getting Started

1. Install Unreal Engine `5.6` through the Epic Games Launcher.
2. Clone the repository:

   ```bash
   git clone https://github.com/TDTer/FristProject.git
   ```

3. Open `FristProject.uproject` with Unreal Engine 5.6.
4. Press **Play** to run the project.

If Unreal Engine asks to rebuild or regenerate project files, accept the operation and reopen the project if necessary.

## Working with Blueprints

The main gameplay Blueprints are located in `Content/Bluprints`, including:

- `BP_FirstCharacter` and `BP_PlayerCharacter`: player character Blueprints.
- `BP_EnemyCharacter`: enemy character Blueprint with AI support.
- `BP_FirstGameMode`: project GameMode.
- `BP_FirstPlayerController`: player controller.
- `BP_FirstPawn`: prototype pawn.
- `BP_AttackComponent` and `BP_HealthComponent`: reusable attack and health logic.
- `BP_EnemyAIController`: enemy AI controller.

These assets can be opened directly in the **Content Browser** to inspect or edit their Blueprint graphs.

## Project Status

This is an ongoing learning project and gameplay prototype. Asset names, systems, and gameplay may change in future versions.

## Asset License Notice

The project includes Paragon Crunch assets and Unreal Engine Starter Content. When redistributing the project or using these assets for other purposes, follow the applicable licensing terms from Epic Games and the respective asset sources.
