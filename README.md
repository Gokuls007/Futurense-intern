# Futurense-intern
This Repositories contains all files related to Futurense Internship

## Contents

- `My Work/Project/minion game.py` - "The Minion Game" (HackerRank): reads a word, scores
  substrings starting with vowels (Kevin) and consonants (Stuart), and prints the winner
  with the score, or `Draw`.
- `My Work/Project/Tic tac toe/Tic-Tac-Toe-GUI.ipynb` - two-player Tic-Tac-Toe in a Jupyter
  notebook, built with `ipywidgets` buttons (3x3 board, Reset Board and End Game buttons).
- `My Work/Documents/Emerging Trends in AI and ML - Jan 20 2024.docx` - write-up on emerging
  trends in AI and ML.
- `MoMs/` - minutes of meetings from the internship (January 2024), as `.doc` / `.docx`.
- `Reference Material/` - PDFs: internship schedule, git cheat sheet, and Linux basics
  (basic commands, filesystem, fundamentals).

## Running

```
python -m venv .venv
.venv\Scripts\activate          # Windows (source .venv/bin/activate elsewhere)
pip install -r requirements.txt
python "My Work/Project/minion game.py"
jupyter notebook "My Work/Project/Tic tac toe/Tic-Tac-Toe-GUI.ipynb"
```

The Tic-Tac-Toe board is interactive, so it has to be opened in Jupyter Notebook or
JupyterLab (widgets do not render in a plain Python shell).
