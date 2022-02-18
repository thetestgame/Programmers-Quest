Programmer's Quest!
===================

[![Programmers Quest Primary CI](https://github.com/thetestgame/programmers-quest/actions/workflows/ci.yml/badge.svg?branch=develop)](https://github.com/thetestgame/programmers-quest/actions/workflows/ci.yml)

Programmer's Quest! The open source Python 3 2D MMORPG showcasing the power of Panda3D, Distributed Objects, and the Astron server built by a industry professional. This project is still a work in progress.

This project depends on external Azure resources to function properly. To contribute to this repository make sure you have a valid Azure and PlayFab account to make the required resources. To keep this open to everyone a development environment should all be able to run under the free tier of their respective services.

## Preparing an Environment

To create a new working environment for Quest run the following commands from the directory you would like the repository to be placed.

```
git clone --recurse-submodules https://github.com/thetestgame/programmers-quest quest-src
cd quest-src
python -m pip install -r quest/docs/requirements.dev.txt
```

## Development Build

To run a development client build from source run the following command in the repository root
```
python -m quest.client
```

This will boot the game with paths defined for the source directory as well as provide useful developer hotkeys.
| Hotkey |               Description               |
|--------|-----------------------------------------|
|   F1   | Toggles The ShowBase OOBE mode          |
|   F2   | Reloads the applications source         |
|   F3   | Runs the Panda ls function on the scene |

## Project Commands

The Quest MMO project has numerous commands built in to assist in the development and maintence of the application. A quick summary
of the commonly used commands is as follows.

|  Command   | Description |
|------------|-------------|
| build_apps |             |
| bdist_apps |             |
