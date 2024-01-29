# Number Guessing Game

Number Guessing Game is a python terminal game. Users play against the computer by guessing a number that the computer randomly has chosen. The player can also decide a number and let the computer guess it. 

## How to play

 The computer will ask the user to guess a number between 1 and 25, if the user guess a number that is too high the computer will print "You guessed too high, Guess again!". If the user guess a number that is too low, the computer will print "You guessed too low, Guess again!". If the user guess the right number the computer will print "Congratulations, You guessed right, It was (number)!"

The user can also decide a number and let the computer guess it. The computer will print out "Is (number) too low(L), too high(H), or right(R)?" and the user can choose to press "L" if it is too low, "H" if it is too high or "R" if the number the computer guessed is right. When the computer guesses right the frase "The computer guessed your number, (number)!" will print and the game is over. 

## Features

### Existing features

#### User guessing the number

- The computer will ask the user to enter a name, then greets the user by that name and the game starts.

![Name](https://github.com/matgus217/-number-guessing-game/assets/147818054/3e3a2f1a-9d74-44b7-88ba-5873f7a20b46)

- The computer asks the user to guess a number between 1 and 25.

![MakeAGuess](https://github.com/matgus217/-number-guessing-game/assets/147818054/7701f6b1-10c2-444d-ba32-035829fa648d)

- If the user guesses anything else than a number, a message prints that tells the user that only numbers are allowed.

![Guess](https://github.com/matgus217/-number-guessing-game/assets/147818054/8277dc81-e540-411e-b996-e2c7ca55bd3d)

- The computer print different answers if the user guessed too low, too high or right.

![Guess_High_Low](https://github.com/matgus217/-number-guessing-game/assets/147818054/c3f39d6e-c58a-428e-9f7b-9d2c57c7a5f6)


- The computer print a message and congratulates the user that it was the correct number.

![Result](https://github.com/matgus217/-number-guessing-game/assets/147818054/a79072b3-ea91-42e4-9fdb-b0f76baf9048)

#### The computer guessing the number

- When the user guessed right, it's the computers turn to guess. A message prints that easily explains for the user how it is going to work.

![ComputerTurn](https://github.com/matgus217/-number-guessing-game/assets/147818054/f329e78d-e0d2-48ed-8785-277d30043553)

- The computer prints a message asking the user if the number is too low, too high or right. The user press a key (L/H/R).

![copmuter_guessing](https://github.com/matgus217/-number-guessing-game/assets/147818054/ec40c20c-29b7-4a62-875f-cbd7e4bed053)

- When the computer guesses the right number a message prints.

![ComputerWin](https://github.com/matgus217/-number-guessing-game/assets/147818054/a000a52f-5a67-4414-84d5-6ebac1ef668e)

## Data model

- A user_guess variable that contains the users guesses against the computer.
- Print methods that prints out what is happening in the game.
- A response variable that contains the users answer when the computer is guessing.

## Testing

I have tested the code through a PEP8 linter and confirmed that there are no problems or errors.

![Testing](https://github.com/matgus217/-number-guessing-game/assets/147818054/f8a5c62e-6fe6-4628-9316-6d6e9fe7affd)


### Bugs
There are no bugs.

## Deployment

The project was deployed using Code Institute's moch terminal for Heroku.

Steps I followed for deployment:
- I cloned the repository
- I created a new Heroku app 
- I linked the Heroku app to the repository
- I clicked on Deploy

## Credits
- Code Institute for the deployment terminal
- I searched the internet for ideas for this project and and I learned alot from [GeeksForGeeks](https://www.geeksforgeeks.org/python-programming-language/)
- I've been watching Code Institute's videos for Python Essentials[CodeInstitute](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LS101+2021_T1/courseware/293ee9d8ff3542d3b877137ed81b9a5b/071036790a5642f9a6f004f9888b6a45/?child=first)