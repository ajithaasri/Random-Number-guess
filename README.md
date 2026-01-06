# Random-repository

import random

target_num, guess_num = random.randint(1, 10), 0

while target_num != guess_num:
    guess_num = int(input('Guess a number between 1 and 10 until you get it right: '))

print('Well guessed!')

OUTPUT:

Guess a number between 1 and 10 until you get it right: 1
Guess a number between 1 and 10 until you get it right: 3
Guess a number between 1 and 10 until you get it right: 6
Guess a number between 1 and 10 until you get it right: 8
Guess a number between 1 and 10 until you get it right: 10
Well guessed!
