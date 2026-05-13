# DESCRIPTION

## - 1 - Displaying server information over DigiLab LCD display screen
We plan on using our DigiLab LCD-Screen to display certain information of the Minecraft server, informations involve:

- Player count
- Server weather
- Gamemode

Due to the display only having space for two lines of text, we plan on showing a diffrent statistic every 5 seconds in line:
First the player count, second the weather, and finally the gamemode

## - 2 - DigiLab LEDs represents player's health in-game
The DigiLab also disposes of 16 LED devided into two groups of 8 which displays the players Health in-game. A Minecraft player
disposes of 9 hearts so we will have to use one entire group of LEDs plus one LED from the other group.

## - 3 - NodeRed dashboard as an overview
During this project we are also asked to use the NodeRed dashboard nodes, so we are using them to display an overview
server information, the dashboard will also contain an input field with the the label **Kick**, insert the username of the
player you want to kick and the program will kick the player on the server. The Dashboard will also allow to stop the 
Server by clicking a button with the label **STOP SERVER**.

## - 4 - Discord bot lottery and russian roulette minigame
The Discord Bot in this project is used to introduce a lottery and Russian Roulette Minigame in the server, to activate these
Minigames one must type **/LT** for lottery and **/RR** for russian roulette in the Discord Server.

## - 5 - DigiLab lever used to control time in server
The Lever of the DigiLab will be used to control time in the server, when the signal is 0 the time becomes night, in contrary
if the signal is 1, it becomes day.

## - 6 - DigiLab buttons used to give player random food item
The DigiLab disposes of two big red buttons and 4 tiny black buttons;
The red buttons give strong foods, foods include (from left to right):

- Enchanted golden apple 
- Golden carrot

The black buttons give normal foods, included foods are (from left to right):

- Steak
- Bread
- Watermelon
- Cookie

The player recieves only one item of said foods.

