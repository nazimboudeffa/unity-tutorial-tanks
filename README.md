# Tanks!

A Unity battle game where 2 to 4 players (human or AI) compete in a series of rounds — the first to win 5 rounds takes the game!

Based on the official Unity tutorial: [Tanks! Make a Battle Game for Web and Mobile](https://learn.unity.com/course/tanks-make-a-battle-game-for-web-and-mobile)

> Play the demo: https://play.unity.com/en/games/3772f049-9025-4536-8ede-d93718dace14/tanks

---

## Features

- 2 to 4 players per match
- Human and AI (computer-controlled) tank support
- Customizable tank colors per player
- Round-based gameplay — first to 5 round wins takes the match
- Dynamic camera that frames all active tanks
- Multiple tank prefab variants

## Project Structure

```
Assets/_Tanks/
├── Art/            # 3D models, textures, materials
├── Audio/          # Sound effects and music
├── Prefabs/        # Tank and UI prefabs
├── Scene/          # Game scenes
├── Scripts/        # All C# game logic
│   ├── Managers/   # GameManager, TankManager
│   ├── Tank/       # TankMovement, TankShooting, TankHealth
│   ├── Camera/     # CameraControl
│   └── UI/         # Menu and HUD scripts
├── Settings/       # Input and game settings
└── Tutorial_Demo/  # Assets used in the web demo
```

## Getting Started

### Requirements

- Unity 6 or later (check `ProjectSettings/ProjectVersion.txt` for the exact version)

### Running the Project

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project in Unity Hub.
3. Open the main scene located in `Assets/_Tanks/Scene/`.
4. Press **Play** in the Unity Editor.

## Gameplay

- Select 2 to 4 players in the main menu (human or AI).
- Each player chooses a tank color.
- Rounds start automatically — destroy enemy tanks to win a round.
- The first player to win **5 rounds** wins the game.

## License

This project is based on Unity's official tutorial assets. See [`Assets/_Tanks/Tanks!_Third-PartyNotice.txt`](Assets/_Tanks/Tanks!_Third-PartyNotice.txt) for third-party notices.
