# Aimrite - Battlerite Aimbot
A simple hackathon like project based around the game http://store.steampowered.com/app/504370/Battlerite/

[![Alt text](https://img.youtube.com/vi/qklJei0Me3s/0.jpg)](https://www.youtube.com/watch?v=qklJei0Me3s)

https://www.youtube.com/watch?v=qklJei0Me3s

# Build (Windows)
Change ```SCREEN_WIDTH```, ```SCREEN_HEIGHT```, ```WINDOW_WIDTH``` and ```WINDOW_HEIGHT``` definitions to your screen dimensions.

To build simple clone and open the solution in Visual Studio 2015 and build under Debug x86

It's recommended that you play on locked screen.

Note : if Battlerite has updated since the last commit then it's quite likely that you will have to update ```Offsets.hpp```.

# Use
Simply have Battlerite.exe open and then run this program.

Uncomment Jade "scripts" (Anti-gap closer and auto shift right click) in main.cpp if you want to use them.

Hold mouse button 5 to disable aimbot.

# Todo
Find offsets for if player is countering, to implement ignore countering players

Find offsets for player health, to target lower enemies or to steal orb with snipe at 44 health

Find entity of orb, to steal it