# 🎯 Number Guessing Game

An interactive Python command-line game where the program randomly selects a number and guides the player to the answer through directional hints. Features difficulty levels and guess tracking.

---

## Features

- ✅ Random number generation within a selectable range
- ✅ Directional feedback ("Too high" / "Too low") after each guess
- ✅ Guess counter displayed at the end
- ✅ Multiple difficulty levels (Easy, Medium, Hard)
- ✅ Replay option after each round

---

## Demo

```
=== Number Guessing Game ===

Select difficulty:
  [1] Easy   (1 – 50)
  [2] Medium (1 – 100)
  [3] Hard   (1 – 500)

Your choice: 2

I'm thinking of a number between 1 and 100.

Guess: 50
  → Too low! Try higher.

Guess: 75
  → Too high! Try lower.

Guess: 63
  → Too low! Try higher.

Guess: 69
  🎉 Correct! You got it in 4 guesses.

Play again? (y/n):
```

---

## How to Run

**Requirements:** Python 3.x

```bash
# Clone the repository
git clone https://github.com/f-anselm88/number-guessing-game.git

# Navigate into the project
cd number-guessing-game

# Run the program
python guessing_game.py
```

---

## What I Learned

- Using Python's `random` module for number generation
- Building replayable game loops with `while` and `break`
- Tracking state (guess count) across iterations of a loop

---

## Author

**Anselm Munango**
[f-anselm88.github.io](https://f-anselm88.github.io) · [GitHub](https://github.com/f-anselm88) · [LinkedIn](https://linkedin.com/in/anselm-munango-bs) · [anselm.mu@gmail.com](mailto:anselm.mu@gmail.com)

