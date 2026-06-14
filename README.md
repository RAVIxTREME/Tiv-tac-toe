# 🎮 Tic Tac Toe 

A browser-based **Tic Tac Toe game** with an unbeatable AI powered by the **Minimax algorithm**.  
Built with vanilla HTML, CSS, and JavaScript — no libraries, no frameworks.

**🌐 Live Demo:** [ravi1game.netlify.app](https://ravi1game.netlify.app/index.html)

---

## 📸 Screenshot

![Tic Tac Toe Game Screenshot](screenshot.jpeg)

---

## ✨ Features

- 🤖 **AI with Minimax** — the AI plays optimally on Hard mode
- 🎯 **3 Difficulty Levels** — Easy (random), Medium (50/50), Hard (unbeatable)
- 🔁 **Reset & New Game** buttons
- 📱 **Responsive Design** — works on mobile and desktop
- ⚡ **Zero dependencies** — pure HTML/CSS/JS in a single file

---

## 🧠 How Minimax Works

Minimax is a recursive algorithm used in two-player games. The AI simulates **all possible future moves**, scores each outcome, and picks the move that maximizes its chance of winning (or minimizes the human's).

| Score | Meaning      |
|-------|--------------|
| +10   | AI wins      |
| -10   | Human wins   |
|  0    | Draw         |

The AI always picks the highest score — making it **impossible to beat** on Hard mode.

---

## 🚀 Getting Started

### Run Locally

```bash
git clone https://github.com/your-username/tic-tac-toe-ai-minimax.git
cd tic-tac-toe-ai-minimax
# Open index.html in any browser
```

No build step needed. Just open `index.html` directly.

---

## 📁 Project Structure

```
tic-tac-toe-ai-minimax/
├── index.html        # All-in-one file (HTML + CSS + JS)
├── screenshot.jpeg   # Game screenshot
└── README.md         # This file
```

---

## ⚙️ Change Difficulty

Inside `index.html`, find this line in the `<script>` section:

```js
let difficulty = "hard"; // "easy" | "medium" | "hard"
```

Change `"hard"` to `"easy"` or `"medium"` and refresh the page.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- ** JavaScript**
- **Minimax Algorithm**

---

## 👨‍💻 Developer

**Ravi Bhosale**  
CSE Student | Maharashtra, India  
GitHub: [@RAVIxTREME](https://github.com/RAVIxTREME)

---

## 📄 License

This project is open source and free to use.
