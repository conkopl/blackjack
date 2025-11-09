This is a brief rundown of how my code works.

Game Setup:
  Card Deck: Creates a standard 52-card deck with 4 suits (Hearts, Diamonds, Clubs, Spades) and shuffles it
  Starting Hands: Both you and the dealer get 2 cards each when the game starts

Card Values:
  Number cards (2-10) = face value
  Face cards (J, Q, K) = 10
  Aces = 11, but automatically count as 1 if needed to avoid busting

Game Flow:
  Your Turn: You see both your cards and their total value. The dealer shows only one card
  
Actions:
  Hit: Take another card from the deck
  Stand: Keep your current hand and end your turn
  
Dealer's Turn: 
  Once you stand, the dealer reveals their hidden card and automatically draws cards until they reach at least 17

Winning Conditions:
  If you go over 21, you bust and lose immediately
  If the dealer busts (over 21), you win
  Otherwise, whoever is closest to 21 wins
  Same values = tie
