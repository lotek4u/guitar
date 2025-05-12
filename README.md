# Guitar Fretboard Visualizer Web App

A fully client-side, interactive web application that visually represents a 6-string guitar fretboard with 22 frets. Built using only HTML, CSS, and JavaScript — no frameworks, no build tools.

---

## 🎸 Features

- **Interactive Fretboard Display**
  - Standard 6-string layout (EADGBE by default)
  - 22 frets with open string and visual nut

- **Tuning Controls**
  - Global down-tuning selector (Standard to A# Standard)
  - Per-string tuning selectors with half-step increments

- **Note Highlighting**
  - Click any note cell to highlight it and all identical notes on the fretboard
  - Selected note: bright green with bold text
  - Matching notes: dark green background

- **Automatic Reset**
  - Clicking outside the fretboard or changing tuning resets highlighting

---

## 📦 How to Use

1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Use the dropdowns to adjust tunings.
4. Click any note cell to highlight all matching notes.

---

## 🔧 Technical Details

- **HTML/CSS/JS Only** — runs locally without a server
- **Monospaced Font** used for dropdown alignment
- **Pure DOM Manipulation** for maximum compatibility

---

## ✍️ Customization

You can easily change:

- Tuning defaults (`standardTuning` in JS)
- Number of frets (`fretPositions`)
- Display behavior (e.g. toggle highlights instead of replacing)

---

## 💡 Future Ideas

- Add support for highlighting chords
- Add support for 7 or 8-string guitars
- Add frequency or interval overlays

---

## 📄 License

MIT License — free to use, modify, and distribute.
