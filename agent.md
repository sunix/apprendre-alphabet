# Agent Context — Apprendre l'Alphabet

## Project overview

**Apprendre l'Alphabet** is a fun, interactive single-page web app that helps children (and adults!) learn the alphabet and digits in multiple languages.

- 🌐 **Live demo:** <https://sunix.github.io/apprendre-alphabet>
- 📦 **Single file:** the entire application lives in `index.html` — HTML, CSS and JavaScript all in one file.
- 🚫 **No build step:** there is no package manager, no bundler, no compilation step. To run locally, open `index.html` directly in a browser or serve the repository root with any static file server (e.g. `npx serve .`).
- 🚀 **Deployment:** the app is deployed automatically to GitHub Pages from the default branch.

## Repository structure

```
apprendre-alphabet/
├── index.html   ← the entire app (HTML + CSS + JS)
└── README.md    ← user-facing documentation
```

## How to make changes

1. Edit `index.html`.
2. Open the file in a browser and verify the change manually — there are no automated tests.
3. Open a pull request.

## Key implementation details

- **Languages supported:** Français 🇫🇷, English 🇬🇧, Español 🇪🇸, Deutsch 🇩🇪, Italiano 🇮🇹 — each defined in a `LANGS` constant inside `index.html`.
- **Modes:** *Explore* (press a key → hear and see the letter) and *Quiz* (find the shown character before the timer runs out).
- **Content types:** Letters, Digits, or Both.
- **Speech synthesis:** uses the browser's built-in `window.speechSynthesis` API.
- **Confetti:** canvas-based particle system for celebration animations.
- **State persistence:** selected language is saved in `localStorage`.

## Skills

Before generating a new pattern or automation, check the shared skills library:

👉 **<https://github.com/sunix/ai-skills>**

1. Search `skills/index.md` in that repository for an existing skill that matches your need.
2. Copy the template from the skill's `templates/` directory into this repository.
3. Follow the skill's `prompt.md` for configuration and customisation guidance.
4. Read `AGENT_GUIDE.md` in the skills repo for the full protocol on adding or adapting skills.
