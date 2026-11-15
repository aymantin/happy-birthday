# 🎂 Make a Wish

An interactive birthday surprise that runs in the browser. Enter a secret code, watch the cake rise, light the candles, hold **SPACE** to make a wish, and enjoy the celebration finale with confetti and fireworks.

Built with plain **HTML, CSS and JavaScript** (single file, no dependencies, no build step).

## ✨ Features

- 🔐 Code-protected entry page
- 🎬 Cinematic flow: title → rising cake → candles → wish → finale
- 🕯️ Animated candle flames and warm glow, all drawn on `<canvas>`
- 🎆 Fireworks, falling confetti and a spotlight beam
- 📱 Works on desktop and mobile (tap and hold instead of SPACE)

## 🚀 Getting Started

### Option 1: Open directly
Download the repo and double-click `index.html`.

### Option 2: VS Code + Live Server
1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` → **Open with Live Server**.

## 🎮 How to Play

| Step | Action |
|------|--------|
| 1 | Enter the secret code and press **Enter** |
| 2 | Press **Enter** on the title screen to begin |
| 3 | Watch the candles light up |
| 4 | **Press and hold SPACE** (or tap and hold on mobile) until the bar fills |
| 5 | Enjoy the finale, press **R** to replay |

## 🔧 Customization

**Change the secret code:** open `index.html` and edit this line near the top of the `<script>`:

```js
const SECRET = '28112010';
```

**Change the messages:** search for the `say(...)` calls in the script and edit the text.

**Change the colors:** gold tones are in the `.gold` CSS class, the background colors are in the `background()` function.

## 📁 Project Structure

```
make-a-wish/
├── index.html   # everything: markup, styles and script
└── README.md
```

## ⚠️ Note on the Code Gate

The code check happens in the browser, so anyone who views the page source can find it. It's meant as a fun surprise gate, not real security.

## 🛠️ Tech

- HTML5 Canvas
- Vanilla JavaScript
- CSS3 (Google Fonts: Cinzel & Cormorant Garamond)

## 📄 License

Free to use and modify for personal projects. Add your preferred license (e.g. MIT) here.

---

Made with ❤️ for someone special.
