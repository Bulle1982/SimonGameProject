
---

## ✨ Features

- Dynamic level display (`Level 1`, `Level 2`, ...)
- Flashing buttons with unique sounds
- Error sound and red screen effect on incorrect input
- Reset functionality with one key press
- Retro 8-bit aesthetic using Google Font: **"Press Start 2P"**

---

## 🛠 Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- jQuery  
- Google Fonts (Press Start 2P)

---

## 🐞 Known Issues & Suggestions

- ✅ Fix HTML typo:  
  Replace  
  `<div lass="row">`  
  with  
  `<div class="row">`

- 🔈 Ensure the following `.mp3` files exist in a `sounds/` folder:
  - `red.mp3`
  - `blue.mp3`
  - `green.mp3`
  - `yellow.mp3`
  - `wrong.mp3`

- 📱 Improve mobile responsiveness.
- 🧮 Add scoring system (optional).

---

## 🧪 Game Logic Overview

- `gamePattern[]`: Stores the generated sequence.
- `userClickedPattern[]`: Stores the player's clicks.
- `checkAnswer(index)`: Validates user input at each step.
- `nextSequence()`: Adds a new color to the sequence each level.
- `startOver()`: Resets the game on error.

---

## 📜 License

MIT License — free to use and modify for learning or personal projects.

---

## 🙌 Acknowledgements

- Inspired by the original **Simon** game by Milton Bradley.
- Retro fonts from [Google Fonts](https://fonts.google.com/specimen/Press+Start+2P).
