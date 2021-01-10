# Crude-space-invader-TivaC
## Disclamer: 
### The game is not fun to play and has only 2 levels, but it was made to demosntrate the skills I gained studying arm cortex-M4 processor.

## Description:
### This is a crude copy of the famous classic game space invaders that is not ported from 
### the original but built from scratch which is running on the tivaC development board
### from texas instrument based on Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 80MHz.
### This game has two threads the main thread (forground thread) and and interrupt thread
### (background thread).
### The background thread (interrupt) is triggered 30 times per second to achieve smooth 30
### frames per second for the player and acts as the game engine as it updates 
### the game world with movements and trigerred actions.
### The main thread refreshes the screen buffer then displays it and checks for the levels
### and the end game.
### _____________________________________________________________________________________________
### The development enviroment i used to make this project is KEIL-MDK-4.7 the evaluation version.
### _____________________________________________________________________________________________
### Here is a link of me running the game fully on a simualated enviroment on my pc --> https://youtu.be/pU9qwnmwMx8
### Note: 
### Since the game is run on simulated hardware it is at least five times slower than on real hardware.
