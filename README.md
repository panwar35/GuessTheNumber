# 🎲 Guess My Number!

A fun, interactive browser-based number guessing game where players try to guess a randomly generated secret number within a customizable range. Built with HTML, CSS, and JavaScript.

![Game Screenshot]()

## 🎮 How to Play

1. The game generates a random secret number between **1** and your chosen maximum range (default: 20)
2. Type your guess in the input field and click "Check!" or press **Enter**
3. You'll receive hints if your guess is too high or too low
4. Your score starts at 20 and decreases with each wrong guess
5. Guess the correct number to win and potentially set a new high score!
6. Click "Again!" to start a new round

## ✨ Features

- **Dynamic Range**: Customize the maximum number range (minimum 20)
- **Score System**: Start with 20 points, lose 1 point per wrong guess
- **High Score Tracking**: Saves your best score using sessionStorage
- **Close Guess Detection**: Special messages when you're within 2 numbers of the secret
- **Sound Effects**: Audio feedback on button clicks
- **Keyboard Support**: Press Enter to submit guesses or change range
- **Visual Feedback**: 
  - Red flash animation for wrong answers
  - Green background on correct guess
  - Dark red background when score reaches 1
- **Responsive Design**: Works on desktop and mobile devices

## 🎯 Game Mechanics

- The secret number changes when you:
  - Start a new game (via "Again!" button)
  - Change the range and press Enter
- **Win Condition**: Guess the secret number before your score reaches 0
- **Lose Condition**: Score reaches 0 without guessing correctly

## 🛠️ Technologies Used

- HTML5
- CSS3 (with animations and responsive design)
- JavaScript (ES6+)
- Google Fonts (Press Start 2P)
- Session Storage API

## 📁 Project Structure

