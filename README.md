# Hangman Game (C)

### 🎓 Context
This is a classic Hangman game developed in **C** to explore file handling (`FILE I/O`), dynamic randomized selection, and string manipulation. It marks an evolution in my early studies, moving from simple user input to interacting with external data sources.

### 🚀 Features
* **External Word Bank:** Loads a list of words from a `.txt` file, allowing for easy expansion of the game's vocabulary.
* **Randomized Gameplay:** Uses `srand` and `time` to ensure a different word is selected in every session.
* **Visual Feedback:** Dynamic ASCII art represents the hangman's states based on the number of errors.
* **Input Validation:** Prevents repeated guesses and ignores non-alphabetic characters.

### 🛠️ Technical Details
* **File Management:** Implements `fopen`, `fscanf`, and `fgets` to parse the word list and select a specific line.
* **State Management:** Tracks correct guesses, mistakes, and used letters using arrays and pointers.
* **Command Line Arguments:** The game expects the path to the word list as an argument (`argv`), demonstrating a more advanced use of the `main` function.

### 💻 How to run
1. **Compile** the code:
   ```bash
   gcc forca.c -o forca

2. **Run** the game by providing the word list file:
   ```bash
   ./forca palavras.txt
