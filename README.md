# Sokoban

## Overview

Sokoban is a computer game of the puzzle variety that was created in 1980, and is available on many computer platforms. The game involves controlling a worker in a warehouse who has to push boxes around the warehouse to get them onto their destination spots. The worker can only push one box at at time, and cannot pull boxes. It is easy for the player to get stuck in a deadlock where it is no longer possible to move some of the boxes. Some of the levels are extremely difficult to solve.

## Compiling Java files using Eclipse IDE

1. Download this repository as ZIP
2. Create new `Java Project` in `Eclipse`
3. Right click on your `Java Project` --> `Import`
4. Choose `General` --> `Archive File`
5. Put directory where you downloaded ZIP in `From archive file`
6. Put `ProjectName/src` in `Into folder`
7. Click `Finish`
8. Move all the files (not the directory) in the `images` and `levels` directory from `{ProjectName}/src` to the root of your `Java Project` i.e. `{ProjectName}`

### Linking the UI Library

9. Right click on your `Java Project` --> `Build Path` --> `Add External Archives`
10. Select `ecs100.jar` and link it to the project. That JAR will be in the directory where you downloaded ZIP

## Running the program

1. Right click on your `Java Project` --> `Run As` --> `Java Application` --> `Sokoban`

## Notes

<strong>Click on the graphics pane first to activate control using keys.</strong>

## Controls

`WASD` or `IJKL` to move. You can also use `mouse-click` but this does NOT move boxes, just walks to that location if possible

## Features

- Undo
- New Game = Picks new `level` from `<warehouse>N.txt` 
- Restart = Restarts current `level`

## Goal

 Put the boxes away in the designated area
