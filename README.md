# 🎮 Hangman Game

A simple text-based Hangman game built using Python. The game randomly selects a word from a predefined list, and the player must guess the word one letter at a time before running out of attempts.

## 📌 Features

- Random word selection
- 5 predefined words
- Maximum 6 incorrect guesses
- Input validation for user guesses
- Tracks previously guessed letters
- Win and lose conditions
- Beginner-friendly Python implementation

## 🛠️ Technologies Used

- Python 3
- Random Module

## 📂 Project Structure

```text
HANGMAN-GAME/
│
├── hangman.py
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/vedaangprataps-hub/HANGMAN-GAME.git
```

2. Navigate to the project folder:

```bash
cd HANGMAN-GAME
```

3. Run the program:

```bash
python hangman.py
```

## 🎯 Game Rules

1. The computer randomly selects a word.
2. The player guesses one letter at a time.
3. Correct guesses reveal the letter's position in the word.
4. Incorrect guesses reduce the remaining attempts.
5. The player wins by guessing the complete word before running out of attempts.
6. The player loses if six incorrect guesses are made.

## 💻 Sample Output

```text
🎮 Welcome to Hangman!

Word: _ _ _ _ _

Enter a letter: a
✅ Correct Guess!

Word: a _ _ _ e

Enter a letter: p
✅ Correct Guess!

Word: a p p _ e
```

## 🧠 Concepts Used

- Variables and Data Types
- Lists
- Strings
- Conditional Statements (if-else)
- Loops (while)
- User Input Handling
- Random Module

## 📚 Learning Outcomes

This project was developed to practice fundamental Python programming concepts such as loops, conditionals, strings, lists, and user interaction through the console.

## 🔮 Future Improvements

- Difficulty levels
- Larger word database
- Hint system
- ASCII-art Hangman drawing
- Score tracking
- Multiplayer mode

## 👨‍💻 Author

**Vedaang Pratap Singh**

## Internship Project

This project was developed as part of the CodeAlpha Python Programming Internship to strengthen Python programming and problem-solving skills.

⭐ Feel free to fork, improve, and contribute to the project!
