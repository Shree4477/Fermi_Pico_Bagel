🔢 Number Guessing Game (Fermi-Pico)
A simple Python console game where players guess a secret three-digit number, receiving hints after each guess.

📖 About
This project is a fun number guessing game inspired by the classic "Fermi, Pico, Bagels" logic game.
      -Fermi — correct digit at the correct position.
      -Pico — correct digit but wrong position.
      -No output — no correct digits.
The player keeps guessing until they figure out the correct number!

✨ Features
🚀 Real-time hints based on your guess.
🔒 Secret number (currently hardcoded as '234', but can be randomized easily).
🚫 Validation: Only 3-digit, unique-digit numbers are accepted.
🎯 Win when you guess the correct number!

🛠 Technologies Used
      -Python 3
      -Loops and Conditional Statements
      -Basic List and String Operations
      -Set Validation

📂 Project Structure
number_guessing_game.py
README.md

🕹️ How to Play
1. Run the Python script:
    - python number_guessing_game.py
2. Enter a three-digit number.

3. Follow the hints:
    - "Fermi" → correct digit, correct place.
    - "Pico" → correct digit, wrong place.
    -  No hint → no matching digits.

4. Keep guessing until you win!

📸 Example

Enter a three Digit number: 137
valid input
['Pico']

Enter a three Digit number: 234
Fermi Fermi Fermi
You Win


📌 Improvements (To-Do)
    - Randomly generate the secret number.
    - Add attempt counter.
    - Implement "Play Again" feature.
    - Show full leaderboard for multiple players.

🧹 Future Scope:
    🎨 Add GUI using Tkinter or Pygame.
    🌐 Host it as a web game using Flask + HTML/CSS.
    📱 Convert it into a simple mobile app.
