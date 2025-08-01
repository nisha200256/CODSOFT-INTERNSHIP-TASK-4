🎮 Rock-Paper-Scissors Game – Task 4
📌 Overview
The Rock-Paper-Scissors Game is a Python-based interactive game where the user plays against the computer.
The computer makes a random choice between rock, paper, and scissors, and the program determines the winner based on the classic rules:

Rock beats Scissors

Scissors beat Paper

Paper beats Rock

The game also includes score tracking and allows users to play multiple rounds.

✨ Features
User Input – Choose between rock, paper, or scissors.

Computer Random Choice – Computer generates a random selection.

Winner Determination – Logic to decide who wins.

Score Tracking – Keeps track of wins and losses.

Multiple Rounds – Option to continue playing.

User-Friendly Interface – Clear instructions and feedback.

🛠️ Technologies Used
Python 3

random module (for computer’s choice)

🚀 How to Run
Ensure you have Python 3 installed on your system.

Save the program as rock_paper_scissors.py (or run it inside Jupyter Notebook).

Run the script:

bash
Copy code
python rock_paper_scissors.py
Or in Jupyter Notebook, run all cells
📌 Example Output
markdown
Copy code
===================================
   ROCK - PAPER - SCISSORS GAME
===================================
Instructions:
1. Choose rock, paper, or scissors.
2. Rock beats Scissors, Scissors beat Paper, Paper beats Rock.
3. Type 'quit' to exit the game.
===================================

Enter your choice (rock/paper/scissors): rock
🧑 You chose: rock
💻 Computer chose: scissors
🎉 You win this round!
Score - You: 1 | Computer: 0
Do you want to play again? (y/n):
📝 Notes
The program ignores letter case for user input.

Typing quit exits the game at any time.

The score resets when the program restarts.




