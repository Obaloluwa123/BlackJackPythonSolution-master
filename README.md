# BlackJackPythonSolution-master
Blackjack game


❏	How to run the program:
The program can be executed on a computer installed with python3 interpreter using either of these methods:
●	The operating system’s command-line or terminal
●	 Pycharm IDE
Using the operating system’s command-line, open the command-line or terminal, then type python3 followed by the path to the program and click enter.
Using pycharm IDE, ensure pycharm is installed on the computer. Open the program on pycharm and press shift + Alt + f10 or click on  the execute button to run.

❏	What assumptions or choices I made to overcome any lack of clarity found in the instructions? 
Initially I was unclear on how I would solve the complications involved in the ace scoring. Using a dictionary I mapped the card values to their score but since the ace is worth one or eleven points, I had to assume that the actual ace is mapped to eleven then the second ace which  I labelled A1 is mapped to one.

❏	What I did well on the project: 
1.	I made sure I had a thorough understanding of the blackjack game in a real world setting.
2.	I also modularized my code by creating separate methods for almost all the instructions I programmed.
3.	I made sure the output was similar to sample program output.

❏	Rationale on design choices, algorithms decisions made:
The data structure I leveraged on was dictionary, since it involved key value pairs and mapping a key to its associated value, I was able to map the card values to their respective scores and made use of the keys (card values) to return the value (score) instead of creating a loop for every single index of the card value to access the score. This design choice afforded me faster access to elements and reduced the runtime complexity of the program.

❏	Tradeoffs you encountered while programming and how you resolved them: 
1.	Algorithm run time tradeoff was the first issue I needed to resolve using a more optimized data structure that best fits the use case.
2.	Optimizing the intricacies of ace scoring algorithm was another bottle neck I encountered, I resolved it by going through the documentation for a thorough understanding  and using various test cases of multiple aces and value combinations including those given in the document.

❏	What you would improve on the project given more time: 
1. I will improve on optimizing the processing time of the program and the ace scoring algorithm.
2. I would also love to include a GUI showing the suit and value of the card selected.
3. I would write automated test scripts for unit testing using pytest

❏	What manual test you ran on the code:
1.	From a user’s perspective, I wouldn’t take cognisance of the case sensitivity of the program while inputting the H or S to hit and stand. I made sure all user inputs are converted to uppercase so my program wouldn’t throw an error when a user inputs in lowercase.
2.	I tested the code to see if there would be a TIE between the dealer and the player
3.	I tested the code to ascertain that the player with the highest score less than 21 wins the game
4.	I also tested the code to verify that once a player’s score equates to 21, he hits BlackJack and is declared the winner.
5.	I tested that a dealer is declared the winner after revealing his cards and his score is greater than 17 and the other player’s
6.	I tested that if a player with an ace hits and is given another ace, automatically the score of the new ace is 1.
7.	I tested that if the initial cards dealt to a player are both aces, the sum is 12
8.	I tested that if a new card dealt to a player is an ace which sums to be greater than 21, then one is used as the ace scoring instead.
9.	I tested that when a player stands the dealer’s cards are revealed.
10.	I tested that the dealer only hits automatically if the initial sum of cards at hand is less than 17.

❏	How to run any automated test you I created: 
	I wasn't able to create any automated test.

