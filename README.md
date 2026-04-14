# 🏓 Ping Pong Trivia

An interactive trivia game about ping pong — while a ball rallies back and forth between two paddles, you answer questions about history, physics, rules, psychology and equipment. Answer correctly and you score a point. Answer wrong and the rival scores.

Built with pure HTML, CSS and JavaScript. No frameworks, no dependencies, no internet required.

---

## 🎮 How to play

1. Download the file `pingpong_quiz.html`
2. Find it in your Downloads folder
3. **Right-click → Open with → your browser** (Chrome, Firefox, Edge, Safari)

> ⚠️ Don't open it with a text editor or code preview — it needs a real browser to run.

---

## 📋 What's inside

| Detail | Info |
|---|---|
| Questions | 15 |
| Categories | History, Physics, Rules, Benefits, Equipment, Psychology |
| Difficulty | Progressive — gets harder as you go |
| Language | Spanish |
| Dependencies | None |
| Internet required | No |

---

## 🏆 Scoring

Every correct answer sends the ball flying to the rival's side — your score goes up.  
Every wrong answer and the rival returns it — their score goes up.  
At the end you get a final result with accuracy percentage and a verdict based on your performance.

---

## 📁 File structure
pingpong-trivia/
└── pingpong_quiz.html   ← everything is here, one single file

---

## 🛠️ Want to edit the questions?

Open the file in any text editor and look for the `const QUESTIONS` array near the bottom of the `<script>` tag. Each question follows this structure:

```js
{
  category: "Category name",
  icon: "🎯",
  context: "Short paragraph shown before the question appears.",
  question: "The actual question?",
  options: ["Option A", "Option B", "Option C", "Option D"],
  correct: 0,  // index of the correct option (0 = A, 1 = B, 2 = C, 3 = D)
  feedback: "Message shown after answering."
}
```

---

## 📸 Preview

> Pantalla de inicio → animación de ping pong en vivo → contexto por pregunta → resultado final con confetti 🎊

---

*Made with vanilla HTML · CSS · JavaScript*
