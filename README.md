# Lab-12-Final-Golf-Game

Project goals:
Game doc designed amd turned in by 11/23/24. Complete. 
Phase 1: Classes for game sprites completed. Ball, Water, Sand, TinCup  
Phase 2: Classes for labels, buttons and scenes. Complete. 
Phase 3: Defining main function and getting the code to work together between game states. Complete

Instructions:

Golf balls fall from the top and wrap if the hole doesn’t collide. They reset if they collide. 1 point for every “hole in 
one” Water and bunkers come from side to side and wrap.  -1 for bunker -2 for water collisions with golf hole. All arrow 
keys move the hole. Balls reset if they collide with water or sand as well. Water and Sand reset if they collide. 

Game States
Instructions > Game > Instructions can quit from instructions screen

Instructions
	Explains game, shows prev score shows play or quit buttons. Plays theme music. 

Game 
Score in top left, time in top right. All sprites shown, quit with X in corner goes to instruction state

Sprites:
Golf hole: user controlled all arrows move on screen. Can wrap from top to bottom and left to right and vice versa. When 
its ball add 1 point, when hits bunker -1 when hits water, -2.  I took the picture of the hole while playing a round. 
Golf balls: random speed falls from top to bottom. I took a picture of the ball from my golf bag. 
Bunker moves at rand speed from right to left and at rand height. Picture of sand is an edit I did of sand from a picture I 
took on the beach. 
Water moves from left to right, and also is rand speed and height. Water picture is also an edit from a picture I took. 

UI:
Background: picture I took from Barbados Golf Club. 
Timer in top right count down from 10. 
Score in top right
Prev score in instruction screen
Sound effects: 
Coin.wav for ball in hole(You said we could use it!!!) 
drip.wav for water. Originated from Drip1.wav by Neotone -- https://freesound.org/s/75343/ -- License: Creative Commons 0
sand.wav for sand. Shake by qubodup -- https://freesound.org/s/442892/ -- License: Creative Commons 0
theme.wav for instructions screen. 8 Bit Game Theme.wav by Mrthenoronha -- https://freesound.org/s/515615/ -- License: Attribution NonCommercial 4.0 

I really wish I could have used more time and understood a bit more of some of the things we didn't cover in class. Like
gravity, or RPG elements... a turn/time based attack system(think early Final Fantasy games) would have been fun! 


