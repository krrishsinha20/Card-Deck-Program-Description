Card Deck Program
Description
This Java program simulates a deck of 52 playing cards, categorized into four suits and 13 ranks. It provides various functionalities like deck creation, shuffling, dealing cards, and searching for specific cards.

Features & Methods
1. createDeck()
Initializes a deck of 52 cards, assigning each card a suit and rank.
This method is implemented in the constructor of the Deck class.
2. printDeck()
Prints all 52 cards in the deck.
3. printCard(Card card)
Prints a single card in the format: Rank of Suit (e.g., Ace of Hearts).
4. sameCard(Card card1, Card card2)
Checks if two cards belong to the same suit.
Returns true if they do; otherwise, returns false.
5. compareCard(Card card1, Card card2)
Compares two cards based on rank.
Returns true if they have the same rank; otherwise, returns false.
6. findCard(String rank, String suit)
Searches the deck for a specific card by rank and suit.
Returns the card if found; otherwise, returns a message indicating the card is not in the deck.
7. dealCard()
Selects and prints five random cards from the deck.
8. shuffleDeck()
Randomizes the order of cards in the deck using Collections.shuffle().
Code Structure
The program follows an Object-Oriented approach with multiple Java files:

Card.java

Defines the Card class with rank and suit.
Implements a toString() method for proper representation.
Deck.java

Implements the Deck class using an ArrayList<Card>.
Contains methods for deck operations like shuffle, deal, search, etc.
Main.java

Implements a menu-driven program for user interaction.
Uses a Scanner for user input and calls appropriate functions from Deck.java.
How to Run
Clone the repository:
sh
Copy
Edit
git clone https://github.com/krrishsinha20/Card-Deck-Program-Description/tree/b2c84be6afd1bf14e3b5b8b7ec561cfb89d0a4ff
Compile and run the program:
sh
Copy
Edit
javac Main.java  
java Main  
Contribution
Each function and class is committed separately following best coding practices.
Comments are added to explain the logic in each method.
https://github.com/krrishsinha20/Card-Deck-Program-Description/tree/b2c84be6afd1bf14e3b5b8b7ec561cfb89d0a4ff
GitHub Repository












