#Card Counting

##Problem

#####Your task is to set up a card counting training system for prospective gamers to learn how to count cards at the casino. Here are the rules:

##Rules
1. User must be able to enter how many decks they want to play with. Each deck holds 52 cards (2 - 10, J, Q, K, A).
2. The program must then display one card at a time so the user can keep track of the count. The rules are as follows:
	- Count starts off at 4 - (4 * number_of_decks).
	- Cards 2 through 7 increase the count by 1.
	- Count does not change if the card is an 8 or a 9.
	- If the card is a 10, J, Q, K, or A, decrease the count by 1.
4. Provide the user with 4 prompts along the way checking to see if they are keeping track. The program will alert them if their count is correct.
5. Program should then offer the user to play again.
6. Bonus: Randomize the 4 prompts so that they show up at varying times.

##Starter Code

In order to reduce the speed at which the cards come into the user's view, you may want to use a method called `sleep`. This method halts the program's execution for a set amount of time in seconds:

```
sleep(1) #Sleeps for one second
```

You can read more about `sleep` [here](http://www.ruby-doc.org/core-2.1.5/Kernel.html#method-i-sleep).