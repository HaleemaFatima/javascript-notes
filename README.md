# JavaScript Basics — Lab Exam Notes

Interactive, single-file study notes for JavaScript fundamentals, with live practice games and working demos of **React** and **Three.js**. Built for lab-exam prep: read a concept, then immediately practise it in the same page.

Everything lives in one `javascript-basics-notes.html` file — no build step, no install. Open it in a browser and it works.

## Features

- **Core JavaScript notes** — variables, data types, operators, conditions, loops, functions, arrays, objects, and the DOM, each with colour-coded examples and an "exam tip" for the common traps.
- **React section** — components, JSX, props, `useState`, and list rendering, plus a **live counter component** running in the page.
- **Three.js section** — scene / camera / renderer, meshes, and the animation loop, plus a **live 3D scene you can drag to rotate** and reshape.
- **Practice games & activities:**
  - Predict-the-Output quiz (scored, with explanations)
  - React Quick-Check quiz
  - Type Detective (`typeof` explorer)
  - Loop Builder (step-through visualiser)
  - Live JavaScript playground (runs your code, shows errors)
  - Flip flashcards for last-minute revision
- **Design** — purple-and-red theme, responsive down to mobile, keyboard-accessible, and respects reduced-motion settings.

## Getting started

### Option 1 — just open it
Download the repo and double-click `javascript-basics-notes.html`. That's it.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO
```

Then open the HTML file in any modern browser.

### Option 2 — publish it with GitHub Pages
So anyone can view it at a live URL:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/javascript-basics-notes.html`.

> Tip: rename the file to `index.html` if you want it served at the root URL instead.

## Internet requirement

The page works **fully offline** — all notes, quizzes, the JavaScript playground, and flashcards run with no connection.

Three things load from a CDN and need internet the **first time** you open the page:

- Google Fonts (Space Grotesk, Inter, JetBrains Mono)
- React, ReactDOM, and Babel — for the live React counter
- Three.js — for the live 3D scene

If you're offline, those two live demos show a short "needs internet" message; everything else still works.

## Built with

- Plain HTML, CSS, and JavaScript (no framework, no bundler)
- [React 18](https://react.dev/) via CDN — live component demo
- [Three.js r128](https://threejs.org/) via CDN — live 3D scene
- [Babel Standalone](https://babeljs.io/docs/babel-standalone) — to run JSX in the browser
- Google Fonts

## Project structure

```
.
├── javascript-basics-notes.html   # the whole app — notes, games, and demos
└── README.md
```

## Topics covered

| # | Section | What you'll learn |
|---|---------|-------------------|
| 01 | Variables | `let`, `const`, `var` |
| 02 | Data Types | numbers, strings, booleans, `typeof` |
| 03 | Operators | maths, comparison, logic |
| 04 | Conditions | `if` / `else`, ternary |
| 05 | Loops | `for`, `while` |
| 06 | Functions | parameters, `return`, arrow functions |
| 07 | Arrays | indexing, `push`/`pop`, looping |
| 08 | Objects | key–value pairs, dot vs bracket access |
| 09 | DOM | selecting elements, events |
| 10 | React | components, props, state, lists |
| 11 | Three.js | scene, camera, renderer, meshes, animation |

## License

Free to use and modify for studying. Add a license file (for example MIT) if you want to make reuse terms explicit.

---

Made for a JavaScript lab exam. Good luck — go pass it.
