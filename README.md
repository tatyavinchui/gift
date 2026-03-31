# 🎂 Birthday Surprise Web Project

A romantic, multi-page birthday surprise website built with pure HTML, CSS & JavaScript — designed to make someone feel truly special. 💕

---

## ✨ Features

- 🌸 **Landing Page** — Animated falling petals, glassmorphism card, smooth reveal animations
- 📸 **Memories Gallery** — Polaroid-style photo cards with tilt effect, hover tooltips, cursor heart trail
- 🎂 **Cake Page** — Interactive 3-layer cake on a starry night background, blow the candle to trigger confetti + birthday song

---

## 📁 Project Structure

```
birthday-surprise/
│
├── index.html               # Landing page — "Open Your Gift"
├── memoris.html             # Photo memories gallery
├── cake.html                # Interactive cake + music reveal
│
├── img1.jpg                 # Memory photo 1
├── img2.jpg                 # Memory photo 2
├── img3.jpg                 # Memory photo 3
├── img4.jpg                 # Memory photo 4
│
└── happy-birthday-314197.mp3   # Birthday song
```

---

## 🚀 How to Run

1. Clone or download this repository
2. Make sure all images (`img1.jpg` – `img4.jpg`) and the `.mp3` file are in the **same folder** as the HTML files
3. Open `index.html` in any browser
4. Enjoy! 🎉

> No server needed — runs entirely in the browser.

---

## 🎮 User Flow

```
index.html  →  memoris.html  →  cake.html
  (Landing)     (Memories)       (Cake + Song)
```

1. **index.html** — Click "Open Your Gift 🎁" to begin
2. **memoris.html** — Hover over photos to see messages, click "One More Surprise" to continue
3. **cake.html** — Tap the candle flame to blow it out → confetti explodes → play the birthday song 🎵

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (animations, glassmorphism, backdrop-filter)
- Vanilla JavaScript
- Google Fonts (Dancing Script, Playfair Display, Lato)

---

## 💡 Customization

| What to change | Where |
|---|---|
| Name ("Papu") | `index.html` → `<h1>` tag, `cake.html` → `<h2>` tag |
| Birthday message | `cake.html` → `.wish` paragraph |
| Photo captions & tooltips | `memoris.html` → `.caption` and `.tooltip` divs |
| Background music | Replace `happy-birthday-314197.mp3` |
| Photos | Replace `img1.jpg` – `img4.jpg` |

---

## 📸 Pages Preview

| Page | Description |
|---|---|
| 🌸 index.html | Soft blush gradient, floating petals, animated card |
| 📷 memoris.html | Polaroid gallery with tilt, hover effects, heart cursor |
| 🎂 cake.html | Dark starry bg, interactive candle, confetti, music player |

---

Made with 💖 — because some people deserve more than just a text message.
