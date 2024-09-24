The Maze
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 20.04

About SDL2
Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

Installation
$ git clone https://github.com/29126229/The-Maze-project.git
Usage
Execute ./maze or type make run
Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)
Compilation
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`
Author : Vicky Chepkorir Chelangat
