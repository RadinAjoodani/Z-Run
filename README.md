Z-Run
A Rogue-like Adventure in C

Project Overview

Z-Run is a terminal-based, rogue-like dungeon crawler game developed in C using the ncurses library for the graphical interface and SDL for audio. This project was created for the Fundamentals of Programming (FOP) course at Sharif University of Technology. The game challenges players to navigate through randomly generated levels, collect treasure, and survive encounters with various monsters.

Features
This game includes a variety of features designed to create a classic rogue-like experience:

Main Menu & User System:

Sign up with username, password, and email validation.
Secure login system and option to play as a guest.
Password recovery and random password generation options.

Gameplay & Mechanics:

Navigate through 4 floors of a treacherous dungeon.
Procedurally generated maps with multiple rooms and corridors for a unique experience every time.
Engage in combat with a variety of enemies, including Deamons, Giants, Snakes, and more.
Collect gold, weapons, spells, and food to survive and increase your score.

Advanced Features:

Enchanted and Nightmare Rooms: Special themed rooms that alter gameplay, such as limiting vision or containing powerful items.
Interactive Objects: Locked doors, traps, and secret passages to discover.
Audio Integration: Background music using the SDL2_mixer library to enhance the atmosphere.

Scoring & Profile:

A persistent score table that ranks players.
Player profiles to track statistics like gold, kills, and games played.

Controls:

Movement: Use the number pad (1, 2, 3, 4, 6, 7, 8, 9) to move in 8 directions.

Menus:

e: Open the food menu.
p: Open the spell menu.
i: Open the inventory/weapon menu.

Actions:

Spacebar: Attack in a chosen direction.
m: Toggle the full map view.
q: Quit the game and save progress (if logged in).

Getting Started
To compile and run this project on a Linux-based system, follow these steps.

First you need to install ncurses libraries:
sudo apt-get install build-essential libncursesw5-dev libsdl2-dev libsdl2-mixer-dev

Compilation:
Use GCC to compile the source code. The following command links all required libraries:

gcc v6.c -o Z-Run -lncursesw -lSDL2 -lSDL2_mixer -lm

This will create an executable file named Z-Run.

Running the Game
To start the game, simply run the executable from your terminal:

./Z-Run
