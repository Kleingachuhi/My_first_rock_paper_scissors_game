# My_first_rock_paper_scissors_game


This is just a simple representation of the rock, paper, scissors game.

#How it works: 
--> The three options of either rock, paper or scissors are stored in a list and assigned to a variable my_hand_can_be which is basically what one can have since one can either have rock with their fist closed, paper with their palm spread out or scissors with their two fingers in the shape of scissors.

Next up is the my_hand variable which stores the final hand instance. Using the random module, we use the choice method which returns a random value from our list my_hand_can_be.

In our loop we have an input that asks the user what they would like to have as their final gesture and a follow up confirmatory input that checks whether the user is sure or not. If the user is sure they type y and they can either get a Congratulation message of ('Congratulations You have won!') if their input matches the random value from my_hand or an apologetic message of ("Sorry try again!") if their input does not match the random value from my_hand.

If after getting the confirmatory the user types n, then the game  is aborted and a message of ("Unfortunately invalid, try again.") is printed.


Language used:
Python with random module imported.

The demo is not perfect or full proof but it is very simple and just for beginner practice.
