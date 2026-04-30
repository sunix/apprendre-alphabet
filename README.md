# Apprendre l'Alphabet 🔤

A fun, interactive single-page web app to help children (and adults!) learn the alphabet and digits — available in multiple languages.

🌐 **Live demo:** [sunix.github.io/apprendre-alphabet](https://sunix.github.io/apprendre-alphabet)

---

## Features

- **Two learning modes:**
  - 🔍 **Explore** — Press any key on your keyboard; the app displays the letter (upper & lower case) and pronounces it using text-to-speech.
  - 🎯 **Quiz** — A random character is shown; click the matching character in the alphabet row before the timer runs out. Your score is tracked in real time.

- **Three content types:**
  - 🔤 Letters — the full alphabet of the selected language
  - 🔢 Digits — numbers 0–9
  - 📚 Both — letters and digits combined

- **Nine languages:**
  | Flag | Language | Alphabet |
  |------|----------|---------|
  | 🇫🇷 | Français | A–Z |
  | 🇬🇧 | English | A–Z |
  | 🇪🇸 | Español | A–Z, Ñ |
  | 🇩🇪 | Deutsch | A–Z, Ä, Ö, Ü, ß |
  | 🇮🇹 | Italiano | A–Z |
  | 🇯🇵あ | 日本語ひらがな | Hiragana (46 characters) |
  | 🇯🇵カ | 日本語カタカナ | Katakana (46 characters) — type with romaji (e.g. `mi` → ミ, `nn` → ン) |
  | 🇷🇺 | Русский | Cyrillic А–Я (33 letters) |
  | 🇺🇦 | Українська | Cyrillic А–Я (33 letters) |

- **Progress tracking** — each typed or found character is highlighted in the alphabet row.
- **Confetti celebration** 🎉 when all characters have been found.
- **Language preference** saved in `localStorage`.

---

## How to use

### Explore mode
1. Open the app and press any letter or digit on your keyboard.
2. The character appears on screen (upper and lower case) with a unique colour, and is read aloud.
3. Try to type every character in the alphabet to fill the progress bar!

### Quiz mode
1. Switch to **Quiz** mode using the button in the top-right corner.
2. A random character is displayed — find and click it in the alphabet row below.
3. A 30-second timer counts down for each question. Score points for each correct answer!

### Changing the language or content type
- Use the **flag buttons** at the bottom to switch languages at any time.
- Use the **content buttons** in the top-left to switch between Letters, Digits, or Both.

---

## Running locally

No build step needed — the entire app is a single `index.html` file.

```bash
# Clone the repository
git clone https://github.com/sunix/apprendre-alphabet.git
cd apprendre-alphabet

# Open directly in your browser
open index.html       # macOS
xdg-open index.html   # Linux
start index.html      # Windows
```

Or simply serve it with any static file server:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## Contributing

Pull requests are welcome! As the whole app lives in a single `index.html`, edits are straightforward:

1. Fork the repository and create your branch.
2. Edit `index.html`.
3. Test in your browser.
4. Open a pull request.

---

## License

This project is open source. See the repository for details.