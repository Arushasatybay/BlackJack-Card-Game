# BlackJack-Card-Game

This Python script implements a simple text-based version of the popular casino card game Blackjack. The game is played in the terminal, and you'll be prompted to input your decisions during gameplay.

How to Play

1. Run the script in a Python environment (Python 3.x recommended).
2. Follow the prompts to set the number of games you want to play.
3. During each game, you'll be dealt two cards, and the dealer will be dealt two cards (one face-up, one face-down).
4. You'll be prompted to choose between 'Hit' (take another card) or 'Stand' (keep your current hand).
5. The dealer will then reveal their face-down card and take additional cards until their hand value is at least 17.
6. The winner of each game will be determined based on hand values.


Classes

Card
* Represents a playing card with a specific suit and rank.

Deck
* Represents a deck of playing cards. It initializes with a full set of 52 cards and provides methods to shuffle and deal cards.

Hand
* Represents a player's or dealer's hand of cards. It keeps track of the cards in the hand, calculates the hand's value, and provides methods to display the hand.

Game
* This class orchestrates the gameplay. It allows you to play multiple games of Blackjack. It initializes the deck, player's hand, and dealer's hand for each game. It also handles player decisions and determines the winner of each game.

How to Run

1. Copy the entire code provided above.
2. Open a Python environment (e.g., IDLE, Jupyter Notebook, or a code editor).
3. Paste the code into the environment.
4. Run the script.
5. Follow the prompts to play the game.
   
Note
* The script assumes that the user inputs valid choices during the game prompts. Invalid inputs might lead to unexpected behavior.
The script doesn't implement advanced Blackjack rules like splitting or doubling down, and it uses a simplified approach to determining winners.
Enjoy playing the text-based Blackjack game! Feel free to expand and enhance the code to add more features and complexity to the game.
