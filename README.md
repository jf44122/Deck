# Deck
Plan on making a 52 card deck that can be randomized and dealt
Each card should be its own object with a suit and rank key.
  Rank (Two through Ace),
  Suit (Clubs, Diamonds, etc)
  
Possible solutions for creating the deck include
  iterating through two arrays of rank and suit
  assigning each card a rank and suit (not very DRY)
  Turning deck into an array with 0-51 cards, each index value gets assigned a rank and suit
  
Possible solutions for shuffling the deck
  randomly assigning each of the cards position in the deck (using Math.random)
  
  
