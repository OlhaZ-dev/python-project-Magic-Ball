# Python Project Magic Ball
This project is a straightforward implementation of the classic Magic 8-Ball toy using Python (in the current case - Magic 11-Ball). The script generates a random number from 1 to 11 and returns a corresponding "prophetic" answer to a predefined question.

## Key Features:
Personalized Questions: Prints the questioner's name along with the question (e.g., "Motia kitty asks: Will I get a snack today?").

Answer Generation: Uses the random module to select one of eleven possible responses.

Specialized Answers: Includes standard Magic 8-Ball phrases, as well as unique ones ("You will get two snacks!", "You should move more").

Input Validation: Checks if a question has been provided.

## How It Works:
The script sets the name and question at the beginning, and then uses the random.randint(1, 11) function to determine which reply will be assigned to the answer variable and printed to the console.
## Project Structure
- `README.md` — project overview (this file)  
- `magic-ball.py` — main Python script 
- `magic-ball-results.md` — markdown file with sample program output
- `LICENSE` — MIT license
- `.gitignore` — excludes temporary and environment-specific files

## How to Use
You can try the exercises in two ways:

### Option 1 — Online (easiest)
No setup needed — just copy any script from the `scripts/` folder and run it in a browser using  
 [Programiz Online Python Compiler](https://www.programiz.com/python-programming/online-compiler/)  
or any similar tool.

### Option 2 — Locally (if you already have Python)
If Python is installed, you can:
1. Download or clone this repository   
3. Run a file from your terminal or IDE (like PyCharm or VS Code)

Example:
```bash
git clone git@github.com:OlhaZ-dev/python-project-Magic-Ball.git
cd python-project-Magic-Ball
python magic-ball.py