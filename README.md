# Welcome to My Mastermind
***

## Task
Write an implementation of a famous Mastermind game using C language.  
Only listed functions were allowed: 
* printf(3)
* write(2)
* read(2)
* rand() (/ srand())
* time()
* atoi()

## Description
Mastermind is a game composed of 8 pieces of different colors.  
A secret code is then composed of 4 distinct pieces.

The player has 10 attempts to find the secret code.
After each input, the game indicates to the player the number of well placed pieces and the number of misplaced pieces.

Pieces will be '0' '1' '2' '3' '4' '5' '6' '7'.

If the player finds the code, he wins, and the game stops.
A misplaced piece is a piece that is present in the secret code but that is not in a good position.

Player's input is read from the standard input.

The program also receives the following parameters (options):  
* -c [CODE]: specifies the secret code. If no code is specified, a random code will be generated.  
* -t [ATTEMPTS]: specifies the number of attempts; by default, the player has 10 attempts.  
    In case, the user skips the option or inputs invalid character, i.e. a letter or 0, attempts are defaulted. 

## Installation
Run command "make" in the terminal. It will build the target file "my_game"
> make

## Usage
To run the game type in 
> ./my_game

The program accepts options **-c** and **-t** in any order:
- options can not be combined - **-ct** is not allowed

> ./my_game -c 1234 -t 7


### The Core Team

<span><i>Made at <a href='https://qwasar.io'>Qwasar Silicon Valley</a></i></span>
<span><img alt='Qwasar Silicon Valley Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
