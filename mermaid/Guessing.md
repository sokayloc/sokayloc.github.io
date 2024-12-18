```mermaid
flowchart TD
  A[Start] --> B[Generate Random Number]
  B --> C[Prompt User for a Guess]
  C --> D{Is Guess Correct?}
  D -->|Yes| E[Display 'You Win!']
  D -->|No| F[Give Hint: Higher or Lower]
  F --> C
  E --> G[Ask if User Wants to Play Again]
  G -->|Yes| A
  G -->|No| H[End Game]
  H --> I[Display 'Thanks for Playing!']
```

### Assignment: Implementing a Random Guessing Game  
1. First, A number will be generated with a limited to a range of 1 to 100.
2. Next, the player is prompted to guess the generated number. 
3. If the guess is correct, display that the player won. 
4. If false, display a hint that tells the player if it is lower or higher and prompt the user again.
5. If the player wins ask if they want to play again. Otherwise, end the game. 

