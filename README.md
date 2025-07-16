# Quiziz 🎯

[Live Demo](https://quiziz.stefansecrieru.com)

This is my submission for the **ZTM (Zero To Mastery) Challenge #44** — the goal was to build a complete application in **a single HTML file** using only **Vanilla JS, CSS, and HTML**. Despite this limitation, the app is fully functional and easily extendable.

---

## Timestamps

- Initial commit: 08 July 2023
- Complete visual remake: 15 July 2025

---

## Developer Skills Showcased

- Vanilla proficiency
- Responsive design
- Visual design skills
- Color theory understanding

---

## 🧠 What is Quiziz?

**Quiziz** is a lightweight quiz game designed to be both easy to play and easy to modify. Developers can customize the quiz content by simply editing a JavaScript array — no complicated logic, no external files, no frameworks.

---

## ✨ Features

- Fully functional quiz game
- Built with **just one file**
- No dependencies — 100% Vanilla JS, CSS, HTML
- Easily editable question bank
- Multiple correct answers supported
- Responsive design

---

## 🛠 Tech Stack

- **Vanilla JavaScript**
- **Vanilla CSS**
- **Vanilla HTML**

---

## ➕ How to Add or Edit Questions

All quiz questions and answers are defined in a simple JavaScript array:

```js
const solutions = [
    {
        question: 'What can you use to style a Web page?',
        correct: [2],
        answers: ['HTML', 'CSS', 'JS', 'React Js.', 'Svelte']
    },
    {
        question: 'What does HTML stand for?',
        correct: [3],
        answers: ['Hyper Text Markup Lingo', 'Hyper Trait Markup Language', 'Hyper Text Markup Language']
    },
    ...
];
```

**To add a new question:**
1. Add a new object inside the `solutions` array.
2. Define:
   - `question`: The question as a string.
   - `answers`: An array of possible answers.
   - `correct`: An array of indexes (1-based) for correct answers.

✅ That's it! No other changes are needed.

---

## 📦 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/Stefan3002/Quiziz.git
```

2. Open `index.html` in your browser.

---

## 📄 License

MIT — feel free to use, modify, and share.

---

## 🙌 Acknowledgements

Thanks to [Zero To Mastery](https://zerotomastery.io/) for the fun challenge!
