# Blackjack — Python terminal game

A command-line Blackjack game built in Python to practice object-oriented programming and game logic.

## Features

- Standard 52-card deck, shuffling, and dealing
- Interactive Hit/Stand choices
- Dealer draws until reaching at least 17
- Win, bust, and tie messages
- Multiple games per session

## Run

Python 3 is required; no external packages are needed.

```bash
python "blackJack Game Project.py"
```

Enter how many games you want to play, then choose `hit`/`h` or `stand`/`s` when prompted.

## Code design

- `Card` — suit and rank
- `Deck` — card collection, shuffle, and deal
- `Hand` — cards and score calculation
- `Game` — input, game flow, dealer logic, and outcomes

## Known limitation

The current ace-scoring implementation adjusts the total for only one ace. Hands containing multiple aces may not be scored correctly. This is a learning project, not a complete implementation of casino rules.

