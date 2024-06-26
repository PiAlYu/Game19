# Game19 Library #

## What is this? ##
The module allows you to perform 19 numbers in just three lines.

## Quick Guide ##
The module is based on the following structure:

    
    for s in range(1, 50):
        if game_all(tuple([i]), '>=65', '35', '+1 +2 *3', 2):
            print(i)
    
Which Python provides by standard.


----------


### Using ###


Using the library is as simple and convenient as possible:

Let's import it first:
First, import everything from the library (use the `from `...` import *` construct).

The function is used by calling it and specifying the necessary input data:

    game_any(array, fin_value, fin_pos, moves, player, step)


There are several input parameters:

    array (tuple) - the input number of units
    fin_value (str) - the final value
    fin_pos (str) - finishing position
    moves (str) - possible moves (separated by a space)
    player (int) - the number of the current player
    step (int) - the number of the current step


There are several functions:

    game_any - a giveaway game with rivals
    game_all is a game with a reasonable opponent
    game_any_sum is an analogue of 'game_any' only with an output of the amount
    game_all_sum is an analogue of 'game_all' only with an output of the amount


An example of using one of the functions:

    for s in range(1, 65):
        if game_all(tuple([s]), '>=65', '35', '+1 +2 *3', 2):
            print(s)
    

*The input array can consist of any number of elements.

----------

## Developer ##
My GitHub: [link](https://github.com/PiAlYu/Game19/) 
