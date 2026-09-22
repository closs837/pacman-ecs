# Pacman (Unity, ECS)

A Pacman clone built in Unity for a game-programming assignment, laid out as an
entity–component–system instead of a pile of MonoBehaviours:

- `Assets/Scripts/Accessor/` — storage for the components.
- `Assets/Scripts/Module/` — the behaviour components (Pacman, edible, kill player,
  score, follow target).
- `Assets/Scripts/Updater/` — the systems that tick those components each frame,
  registered through `UpdateManager.cs`.

Open `Pacman_ECS.sln` or the project folder in Unity 2019.3.15f1 (`ProjectSettings/`)
and run the scene under `Assets/Scenes/`. The scene, prefabs, sprites and animations are
all first-party — no asset-store packs.
