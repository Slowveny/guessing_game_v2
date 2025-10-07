## 10/6/2025 - Day 13

### In this project, you need to choose a mode (Easy, Medium or Hard), and my program will randomly choose a number according to the mode!
&nbsp;

## Version 2
### In this uptaded version of my project, I added multiple difficulty levels (Easy, Medium, and Hard), implemented tracking of the number of attempts until the correct number is guessed, and included a `while` loop so the user can play the game multiple times without restarting the program!


&nbsp;

## Examples
```
Input
Choose the difficulty level:
[ 1 ] Easy
[ 2 ] Medium
[ 3 ] Hard
Chosen level: 2
Try to guess the number I thought of (from 1 to 50): 34
```
```
Output
Your guess was ABOVE the number I thought of.
```
```
Input
Try to guess the number I thought of (from 1 to 50): 20
```
```
Output
Your guess was BELOW the number I thought of.
```
```
Input
Try to guess the number I thought of (from 1 to 50): 25
```
```
Output
Your guess was BELOW the number I thought of.
```
```
Input
Try to guess the number I thought of (from 1 to 50): 27
```
```
Output
* You GOT IT! I was thinking of the number 27
* Number of attempts: 4
```


&nbsp;

## Creation
#### To create this project, I used `import random` to generate random numbers, `while` loops to keep the game running until the user guesses correctly or decides to stop, and conditional statements to handle difficulty levels, check the user's guesses, and give feedback!
