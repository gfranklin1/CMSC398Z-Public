# CMSC398Z - Effective use of AI Coding Assistants and Agents

Welcome to my repository for ```CMSC398Z - Effective use of AI Coding Assistants and Agents``` at the ```University of Maryland, College Park```. This repository includes a summary and the grade received for the homeworks and projects that I completed throughout this course. Due to university policies, the code for these projects is not publicly available. If you are an employer or have a legitimate request to view the code, please contact me directly.

## Assignments 

### Project 1: **Play Wordle**
**Description:**  
- Implemented a command-line Wordle game in Python.
- Used the `termcolor` library to display colored feedback for each letter:
  - White on green for correct letter and position.
  - White on yellow for correct letter, wrong position (with Wordle-style duplicate handling).
  - White on black for incorrect letters.
- Accepted the answer word as a command-line argument.
- Validated user guesses for length and alphabetic characters.
- Allowed up to 6 attempts per game.
- Congratulated the user on a correct guess, or revealed the answer after 6 unsuccessful tries.
- **The entire project was written using Copilot coaching mode as an introduction to AI Agents; I did not write any code myself.**

**Grade:** 

---

### Project 2: **Documenting a Markov Model Text Generator**  
**Description:**  
- Given a fully implemented Markov model text generator, the task was to add proper **docstrings**, **comments**, and **code documentation**.
- The Markov model generates random text based on an input corpus, using a configurable `n`-order model (default 2), and colors the output based on the model’s entropy (i.e., how many different next words could be chosen).
- Docstrings were added for:
  - The `MarkovModel` class.
  - All methods including `__init__`, `reset()`, `saw()`, `learn_from()`, `predict()`, and the helper function `entropy()`.
  - The `main()` function handling command-line input and generation loop.
- Comments were added to explain:
  - Every class attribute and its role.
  - Non-obvious control flow such as special handling for all-uppercase lines, paragraph breaks, and entropy-based coloring.
- **Used GitHub Copilot as a pair-programmer** to help generate initial documentation and explain unfamiliar parts of the code.
- **Did not modify or add to the original code logic**, only focused on understanding and documenting it correctly.
- Verified functionality and behavior using breakpoints and debugger to ensure accurate documentation of edge cases and design choices.

**Grade:**

---

### Project 3: **Poker Analysis**
**Description:**  
 - Implemented a Python-based poker-hand analysis tool that examines a set of seven playing cards and determines the best 5-card poker hand.
 - Core logic lives in `poker_analysis.py` and includes functions to evaluate 5-card hands (`evaluate_five`) and to choose the best 5-card hand from seven cards (`best_hand_from_seven`).
 - Supports the three test levels described in the assignment: (1) identify the best hand rank, (2) identify which cards contribute to that rank, and (3) return the five ordered cards used for hand comparisons.
 - Uses the provided `hand_rank.py` enum for hand categories and includes a test harness and unit tests (`test_harness.py`, `test_poker_hand.py`) plus a `testData/` directory with cases for each hand type.
 - Includes optional side-quest functionality (example code and notes) to simulate completing partial hands and to estimate percentile/chance of final hands or win/tie probabilities against opponents.
 - **The entire project was written using Copilot coaching mode as a continuation on how AI Agents work; I did not write any code myself.**

**Grade:** 

---

### Project 4: ****  
**Description:**  


**Grade:**

---

### Project 5: ****
**Description:**


**Grade:**


---

## Disclaimer

**## CONTACT ME IF YOU WOULD LIKE TO SEE THE CODE, UNDER UNIVERSITY RULES I AM NOT ALLOWED TO POST PUBLICLY ON HERE**

If you are interested in reviewing the code or have any questions related to the projects, please reach out to me directly.
