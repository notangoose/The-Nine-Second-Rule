# The Nine Second Rule

[![Build project](https://github.com/notangoose/The-Nine-Second-Rule/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/notangoose/The-Nine-Second-Rule/actions/workflows/main.yml)

## Description

_The Nine Second Rule_ is a 2D platformer game made in Unity.

## Downloads (<https://nightly.link>)

- [Linux 64-bit](https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/main/Build-StandaloneLinux64.zip)
- [macOS Universal](https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/main/Build-StandaloneOSX.zip)
- [Windows](https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/main/Build-StandaloneWindows.zip)
- [Windows 64-bit](https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/main/Build-StandaloneWindows64.zip)

Alternatively, use `nightly.link` to generate a download link for a specific branch other than `main` (the branch that'll be used for full game releases).

#### Linux and Windows

Linux and Windows builds do not need any special permissions to run.

#### macOS

macOS builds are not signed yet, so permissions are needed to run them.

1. Open _Terminal_ and run the following command:

   ```bash
    chmod +x ~/Downloads/The\ Nine\ Second\ Rule\ -\ StandaloneOSX.app/Contents/MacOS/The\ Nine\ Second\ Rule
   ```

2. Open the game as an administrator, by right clicking and clicking 'Open' in the context menu.

### Notes on Downloads

1. View branches [here](https://github.com/notangoose/The-Nine-Second-Rule/branches) and pick one.
2. Copy the branch name (e.g. `main`).
3. Use the link `https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/<BRANCH>/Build-Standalone<PLATFORM>.zip`.
   |                 | \<BRANCH>                           | \<PLATFORM>                              |
   | --------------- | ----------------------------------- | ---------------------------------------- |
   | Description     | Branch to get the latest build from | Platform to build for                    |
   | Accepted values | Any branch name from step 2         | `Linux64`, `OSX`, `Windows`, `Windows64` |
   | Example         | `main`                              | `OSX`                                    |

   **Examples:**
   `main` branch, macOS: `https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/main/Build-StandaloneOSX.zip`
   `cool-new-feature` branch, Windows 64-bit: `https://nightly.link/notangoose/The-Nine-Second-Rule/workflows/main/cool-new-feature/Build-StandaloneWindows64.zip`

## Controls

There is currently no information about controls in the game, so here you go:

| Control       | Keys           | Description                                 |
| ------------- | -------------- | ------------------------------------------- |
| (Double) Jump | W, Up Arrow    | Travel across large gaps and scale walls    |
| Fallthrough   | S, Down Arrow  | Fall through one way platforms              |
| Move Left     | A, Left Arrow  | Traverse the level and hold walls           |
| Move Right    | D, Right Arrow | Traverse the level and hold walls           |
| Select Level  | Escape         | Play another level or quit the game         |
| Reset         | R              | Respawn the player at the starting position |
| Dash          | Space          | Run faster than ever before                 |

## Game Elements

- **Platform**
  - Horizontal
  - Both sides have collision
  - Always supports you :D
- **One Way Platform**
  - Like a **Platform**
  - Fall through it with the _Fallthrough_ key
- **Wall**
  - Vertical
  - Both sides have collision
  - Can be scaled easily by moving towards it and jumping like no-one's watching
- **Spring**
  - Jump on it to go higher and higher and higher
  - And higher
- **Spike**
  - Triangular
  - Don't touch!
- **Turret**
  - Shoots projectiles straight at regular intervals
- **Enemies**
  - Diamond shaped
  - Moves back and forth and tries to kill you
- **Key**
  - Looks like a... key
  - Bobs up and down and glows
  - Collect it and finish the level to unlock the next secret level
- **Finish**
  - Circular
  - Get here to win!
