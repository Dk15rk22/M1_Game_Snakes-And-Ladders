# Identify Features

## Introduction
  In this project, a version of the Snakes and Ladders game program in C is developed which will perform snakes and ladders game winning or loosing depending on the input from the user. 
   
## About Game
  The game includes the facilities such as saving and loading the game. The saved games are password protected so that only the authorized user can load the previously saved game. The snakes and ladders game project comprises of multiple functions (scroll down to view the description for each) which can be dealt at ease. Attempt has been made to present the program in user friendly environment.
  
## Objectives
  1. To use different user defined function, to break a program into many simplified parts to deal with and to make it easier to understand the codes too.
  2. To promote the use of array in general programming for simplified version of the program.
  3. To apply the file handling concepts in order to retrieve the player’s data files that contains the data of the players.
  4. To use minimum graphics as far as possible to make the program execute fast but also user friendly side by side.
  5. To use general concept of c language to develop a simple snakes and ladders game that as a whole entertains the user.

## Features
  1. Compatible as multi-player game.
  2. Facility to save the game.
  3. Open the saved game using the password pre-defined by the user.
  4. Use minimum graphics in snakes and ladders as far as possible avoiding complex codes.

## Scope
  1. Users preferring the classical games can switch to the game.
  2. Beginners in computer programming can take hints via the mini project to boost up their programming techniques.
  3. Can be brought in practice in training centers that offers basic programming courses.
  4. Can be the best choice as stress relieving game in the busy life pattern of the people in present life.
  5. Simplicity and efficient is main fact that we get using the c language, so user can execute snakes and ladders in each and every computer almost.
  6. Can be milestone for the programmers trying to learn to build projects in C.

# Research
## Functions Used
### 1. Main()

  This function is the main function. This function contains the control of the whole game. User can switch to resume, new game, load game, save game, tutorial and exit from this function. It calls the respective function as user’s input. In this function user can use pre-defined short cut keys too.

### 2. Save game()

  This part of the program is called from the main function when user wishes to save the game. The player can provide his own password to protect the game from other users. In snakes and ladders, this function calls the password function to get the password from the user. After getting the password the name of game, the name of players, and the value of the player is stored in a file named save.dat that can be reopened further.

### 3. Load game()

  This function enables the users to load the initially saved snakes and ladders game. In order to prevent the unauthorized use of the loaded game, there is a password system that user has to go through before he opens or loads the saved game. In order to get game loaded user has to input the game name and the password per defined or per entered. Password functions is called for password input and for matching of the password and the game name data is read from the data file save.dat.

### 4. Tutorial()

  This function in the program prints the tutorial of the snakes and ladders i.e. the help of the game, color indication and so on. The function uses a data file that contains the tutorial of the game. After printing the tutorial the control is transferred to main function.

### 5. Firstscr()

  This function generates the first screen appeared when the program is executed. This function includes some animations and the snakes and ladders title. This function gets control until unless any key of the key board is hit. If any key of the key board is hit the control flows to main function.

### 6. Main game()

  This is the function from where all the game is executed . From this function firstly the layout of the board is called. Then the vipers and the ladders are printed. Then the dice function is called and returned value is added to respective player’s position. Then after the viper and ladder function is called to check the viper and ladder position. Then after the players are displayed at the new position. At last eofgame function is called in this snakes and ladders if the player’s value equals to 100.

### 7. Layout()

  In this function, the general layout of the board is drawn as like in classical game. This function does not get control for long. As soon as it get the control it prints the layout of the board and the control goes to the main game function.

### 8. Drawviperandladder()

  In this function, the vipers and ladders are drawn on the board. This function is called from the main game function of this viper buzz project. The viper are represented by the red color and the ladders are represented by the green color.

### 9. Dice()

  This function is for the value of the dice as per user’s reaction. In snakes and ladders, his function returns an integer value if any key of the keyboard is hit. The value is returned to the main game function. In addition to the dice rolling, this function holds the screen and also responds to the escape key pressed. If escape key is pressed, it flows control to the main menu else the control flows to main menu.

### 10. Position()

  This is the function locating the player in the board of snakes and ladders. This function prints a white space in the old position and it prints the representation character to the new location as the value of the player. The main aim of this function is to prints the player’s indicator in the respective position.

### 11. Viperandladder()

  In this function the player’s position is compared with the initial position of the ladder and respective value of the player is changed only if the initial value matches. In addition to that this function checks the hit condition also. The control flows to the main game after execution of snakes and ladders.

### 12. Locate(int , int)

  This function is used in our program to set the cursor position on the different location of the screen. It takes two arguments and sets the cursor position according to the arguments.

### 13. Draw()

  In this snakes and ladders game project, draw() function helps to print the dice box and the data of the player on the box. It is called each time loop executes so that it overlaps the initial mesh created. This function displays the player’s current position, player’s name and turn.

### 14. Eofgame(char , int)

  This is the final screen after any one of the player reaches to the position of 100. The main loop of the main game function in this snakes and ladders gets break and this function is called. In this function two arguments are passed i.e. firstly the player’s name and the player’s code. This function has the control until unless a key is pressed.

### 15. Password(char)

  In this function, an address is passed as argument and entered password is returned for the pointer. In this snakes and ladders game project, the character that user input is take and the asterisks are printed in place of the character to avoid the identification. This function is called from save game and the load game.

### 16. Playfilesync(char)

  This function is used in the program to play the sound of the game. This function enables the programmer to embed the sound in their console based program. This function takes the file name to be played. The file to be played should be inwav format.

# 4W's 1H 
## Why
  1. To teach morality lesson for each and every person and which can attain salvation through doing good, whereas by doing evil one will be reborn as lower forms of life.
  2. I'm making this for students to understand the concept of mathematics easily.
  3. It can be used to play by anyone at any place for fun & entertainment purpose too.

## Where
  1. This can be used in our daily lives to do good things & to think in possitive manner.
  2. We can use it in the mathematical calculations & problem solving skills.

## Who
  1. It can be used by public even childern can also play this game.
  2. Can be used as a entertainment purpose for stressed out daily working people.

## When
  1. One can play this when got stressed out and want to have fun.
  2. The project can be used when the children & people are bored with their daily works and need entertainment. 

## How
  1. By playing diligently one can find their desired output as winning the game.
  2. It will be helpful in performing various stategical analysis like which path is safer. This will give improve our mathematical knowledge.

# SWOT Analysis
## Strengths
  1. Allows students to understand the concept of mathematics easily.
  2. It can be exposed to the operations of addition and substraction indirectly.
  3. It is also a suitable activity for leisure time.
  4. This is to promote social skills & interaction among the players.
  
## Weakness
  1. One of the weaknesses of this game is it takes much time.
  
## Opportunities
  1. To learn about the life, which is not means to be a one-sided affair. You will face both the good & bad times.
  2. Childern can understand these terms: forword, backword, before, after,next, which way.

## Threats
  1. Advanced featured games are already in the market.

# High_Level Requirements
| ID   |      Description     |  Status |
|----------|:-------------:|------:|
| HLR_1 |  The user can switch to resume, new game, load game  | Implemented  |
| HLR_2 |    The user can play tutorial  | Implemented  |
| HLR_3 |    The user can save games   | Implemented  |
| HLR_4 |    The user needs viper & ladders   | Implemented  |
| HLR_5 |    The user needs drawn  viper & ladders  | Implemented  |
| HLR_6 |    The user needs location of viper & ladders  | Implemented  |
| HLR_7 |    The user needs unique tokens  | Implemented  |
| HLR_8 |    The user needs layout, dice  | Implemented  |

# Low_Level Requirements
| ID   |      Description     |  Status |
|----------|:-------------:|------:|
| LLR_1 |  List of operations displayed | Implemented  |
| LLR_2 |  Input from the user  | Implemented  |
| LLR_3 |  Exit the game  | Implemented  |
