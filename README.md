# Chess

The initial Chess Game was a high school project built in Python and Pygame
before the emergence of AI. This repository builds on that legacy in Kotlin,
representing an authentic chess app created using novel AI workflows.

The original code is kept in the `legacy/` folder. The code runs and 
plays by the full rules of chess. Minor edits have been made on top of
the original code to fix practically non-existent bugs. To verify that it
works correctly, I used [perft](https://www.chessprogramming.org/Perft) standard
reference positions, including Kiwipete.

## Running the legacy game

```
pip install -r requirements.txt
python legacy/core_logic.py   # play in the terminal
python legacy/gui.py          # play on the pygame board
```
## Side Note

This project was inspired by my work on FIP apps, and I will contribute to it,
as I progress through my work there
