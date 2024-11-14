# EcoQuest-Final
## Project Name: A2 Code Prototype (EcoQuest)

## General Information
The purpose of this project was to adhance my code literacy and learn more about coding with python. Although this project doesn't necessarily solve an issue or problem the purpose of it is supposed to be a fun and educational video game. My video game that I coded is a game about the environment it involves a small fish sprite that navigates its way through the ocean, doging past plastic bags to avoid losing lives, and collecting bonus points along the way. The aim of the game is to collect as many points as possible. Let me show you a quick preview in operation. 

## Technolgies Used 
1. MakeCode Arcade
2. Python

## Features 
1. SpritesKinds (player,enemy,food)
2. Heart life span
3. Point tarcker
4. Overlap features
5. Sound effects

## Screenshots 
![image](https://github.com/user-attachments/assets/7783f771-c1bf-4983-826d-2c5fbd83db13)
![image](https://github.com/user-attachments/assets/3dd72245-a895-471b-8afa-8e8c1b625e95)

## Setup 
The Makecode aracde video game has been attached to this file. It has been set up and download using a tinkergen gamego format. There are no other requirments for the set up. It should be already downloaded onto the game boy ready for you to play !

## Usage 
The way to go about using this game. First off when moving through the game title and instructins you will need to press the letter A on the game boy to move through it, then the only thing you will have to do yourself is control the sprite using the joystick controller. 
1. I coded this ability through controller.move_sprite (hero) and also made sure to code hero.set_stay_in_screen (TRUE) so the sprite doesnt leave the screen makeing it easier for the user.
Then this is how I coded the enemy and food sprites to move around on their own
3. enemy.set_velocity (-50,0)
4. enemy.set_posiiton (160, random range)
"" star.
This is then how the sprite is able to scroe points and loose lives
5. on_overlap_enemy (her, enemy):
6. on_overlap_star (hero, star)
* important to have hero first in these codes as otherwsie they dont work 

## Project Status 
This project is definitley a work in progress however I will not be continuing this project after this date forward. I will no longer be partaking in this project as my class is completed for the semester. Howvever if I was to continue I would want to add more levels to this game more enemy sprites with little instructions in between making it more as on engaging user interface. 

## Room for improvment 
As a first time coder there is space for lost of imporvement 
1. I coded to have sound effects to play when the sprite overlapped with either the enemy or food and I don't belive it worked prooerly- that would be my first area of improvment making sure and learning where I went wrong
2. Cleanign up the code I do feel at times my code looked a little messy, so finding a better way to structure and make it more cohesive
3. I wanted to add another another feature at the end of my game which was to add a second enemy an oil spill and have the spirte avoid it. Howver I couldn't quite figure out how to code it to start after the player had reached ten points. I would need to go back reearch and play around agian with this aspect. For the purppose of the porject I didn't leave in the incorrect code 

## Acknowledgments 
These are a list of refernces that helped me through this project and helped to develop my code lietracy. When I hit a signifcant roadblock I tended to go back and go through these resoruces for guidnace and help 
Activity: Sprite Motion and Events. (n.d.). Microsoft MakeCode. Retrieved November 13, 2024, from https://arcade.makecode.com/courses/csintro1/motion/sprite-motion-event
Class Kicker (Director). (2023, September 26). How to add a realistic jump to your sprite in Makecode Arcade. https://www.youtube.com/watch?v=JAsZvSKViKg
Documentation. (n.d.). Microsoft MakeCode. Retrieved November 13, 2024, from https://arcade.makecode.com/docs
Microsoft MakeCode (Director). (2020a, March 18). How to Make a Platformer Game [Part 1: Intro, sprites, movement & tile map]. https://www.youtube.com/watch?v=9bSX9Q5aP6E
Microsoft MakeCode (Director). (2020b, September 15). How to Add Health Bars to Your MakeCode Arcade Game. https://www.youtube.com/watch?v=m7avrQrLP3M
Tutorials. (n.d.). Microsoft MakeCode. Retrieved November 13, 2024, from https://arcade.makecode.com/tutorials
