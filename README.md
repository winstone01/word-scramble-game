# Word Scramble Game

A responsive **Word Scramble Game** built with vanilla HTML, CSS, and JavaScript.  
Each round generates a scrambled word, displays a hint, and starts a countdown timer. Type your answer, check it instantly, and refresh for a new word.

---

## Features

- **Random word generation** with scrambled letters each round
- **Hint system** to guide the player
- **Countdown timer** (new round resets the clock)
- **Input validation** (empty/incorrect answers are handled cleanly)
- **Refresh Word** to instantly load a new challenge
- Responsive, clean UI that works across screen sizes

---

## Built With

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

---

## Getting Started

### Run locally
1. Download or clone the repo
2. Open `index.html` in your browser  
   *(Optional: run with VS Code Live Server for auto-reload.)*

---

## How It Works

- A word list (with matching hints) is stored in JavaScript.
- On each round:
  - A random word is selected
  - Letters are shuffled for the scrambled display
  - Hint text is shown
  - Timer starts counting down
- When the user submits:
  - The app checks the input against the correct word
  - Feedback is shown (valid/invalid)
  - A new round can be loaded using **Refresh Word**

---

## Project Structure

/
├─ index.html  
├─ style.css  
└─ script.js  

---

## Roadmap / Next Improvements

- [ ] Add difficulty levels (easy/medium/hard) based on word length
- [ ] Add streak scoring + best streak saved with `localStorage`
- [ ] Add “Reveal Answer” (with a small penalty)
- [ ] Add keyboard UX (Enter to check, Esc to refresh)
- [ ] Improve accessibility (focus states, ARIA labels, clearer error messaging)

---

## Author

**Winstone Anderson**  
UI-focused frontend developer building clean, responsive web interfaces.

---

## License

MIT (or your preferred license)
