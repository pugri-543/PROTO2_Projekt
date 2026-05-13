# DESCRIPTION

## - 1 - Displaying Server Information over DigiLab LCD Display Screen
We plan on using our DigiLab LCD-Screen to display certain information of the Minecraft Server, informations involve:

- Player count
- Server weather
- Gamemode

Due to the Display only having space for two lines of text, we plan on showing a diffrent statistic every 5 seconds in line:
First the player count, second the weather on the server and finally the gamemode

## - 2 - DigiLab LEDs Displays Player's health in-game
The DigiLab also disposes of 16 LED devided into two groups of 8 which displays the players Health in-game. A Minecraft player
disposes of 9 hearts so we will have to use one entire group of LEDs + one LED from the other group.

## - 3 - NodeRed Dashboard as an Overview
During this project we are also asked to use the NodeRed Dashboard Nodes, so we are using them to display an overview
server information, This Dashboard will also contain an input field withe the label **Ban**, insert the username of the
player you want to ban and the program will ban the player on the server. The Dashboard will also allow to stop the 
Server by clicking a button with the label **STOP SERVER**.

## - 4 - Discord Bot lottery and Russian Roulette Minigame
The Discord Bot in this project is used to introduce a lottery and Russian Roulette Minigame in the server, to activate these
Minegames one must type **/LT** for lottery and **/RR** for russian roulette in the Discord Server.

## - 5 - DigiLab Lever Used to Control Time in Server
The Lever of the DigiLab will be used to control time in the server, when the signal is 0 the time becomes night, in contrary
if the signal is 1, it becomes day.

## - 6 - DigiLab Buttons used to give player random Food item
The DigiLab disposes of two button, the right button will give the player a random meat related food item, and the left button
gives the player a plant-based food item.
