# Rock Paper Scissors Game

A simple and interactive Rock Paper Scissors game built with HTML, CSS, and JavaScript. The game allows users to play against the computer for a maximum of 10 rounds with real-time score tracking and visual feedback.

## Features

- Responsive UI with clickable rock, paper, and scissors choices
- Real-time update of user and computer scores
- Displays messages for win, lose, or draw after each round
- Tracks rounds played and declares the final winner after 10 rounds
- Visual feedback using color-coded messages for game status

## Demo

![Screenshot](images/demo.png) *(Add your demo screenshot here if available)*

## Technologies Used

- HTML5 for structure
- CSS3 for styling and responsive design
- JavaScript (ES6) for game logic and interactivity

## How to Use

1. Clone the repository or download the source files.
2. Open `index.html` in a web browser.
3. Click on one of the choices (rock, paper, or scissors) to play a round.
4. See your score and the computer's score update after every round.
5. After 10 rounds, the game will declare the final winner.

## Project Structure

rock-paper-scissors/
├── index.html
├── style.css
├── app.js
└── images/
├── rock.png
├── paper.png
└── scissors.png


## Code Highlights

- Game logic implemented in `app.js` using modular functions like `genCompChoice()`, `playGame()`, `showWinner()`, and `showFinalWinner()`.
- Dynamic DOM manipulation to update scores and messages.
- CSS styles ensure a clean, user-friendly interface with hover effects.

## Future Improvements

- Add sound effects to enhance user experience.
- Enable game reset option after 10 rounds.
- Make the layout mobile-friendly with responsive design enhancements.
- Add animations for choices and results.

## License

This project is open-source and free to use under the MIT License.

---

Feel free to contribute or raise issues if you find bugs or want to suggest enhancements!

