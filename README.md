# Tigerlyyy
# Tigerlyyy0 - Digital Arcade of Code

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=36&pause=1000&color=F7941D&width=700&lines=👾+Welcome+to+My+Digital+Arcade!+👾" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="120" alt="GIF" /><br>
  <b><span style="font-size: 1.25em; color: #FFD700;">tigerlyyy0-source</span></b>
</p>

<p align="center" style="font-size:1.1em; color: #FF1493;">
  🌈 <b>Code Wizard | Game Dev | Digital Dreamer</b> 🚀 <br>
  🎮 <b>TETRIS (Glowing Edition)</b> ⬇️
</p>

<p align="center">
  <img src="https://github.com/tigerlyyy0-source/tigerlyyy0-source/raw/main/tetris.svg" width="350" alt="Glowing Tetris" />
</p>

---

### 🦄 About Me

- 🧬 Building code, breaking records
- 🎲 I turn caffeine into glowing pixels
- 🧑‍💻 Mastering Python, JavaScript, C++, and shader magic
- 🌍 Dreaming in algorithms since <i>forever</i>
- 📫 DM me for collabs, memes, or intergalactic missions

---

### ⚡️ Snake? Tetris? Why not both! 🐍🎮

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="Snake Animation" />
</p>

---

## 🚀 Glowing Tetris SVG (Embed in your repo)

```svg
<!-- File: tetris.svg -->
<svg viewBox="0 0 200 250" width="350" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="block-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#fff700;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ff00cc;stop-opacity:1"/>
    </linearGradient>
  </defs>
  <!-- Tetris Blocks -->
  <rect x="20" y="20" width="40" height="40" rx="8" fill="url(#block-grad)" filter="url(#glow)" />
  <rect x="60" y="20" width="40" height="40" rx="8" fill="#00ffe7" filter="url(#glow)" />
  <rect x="100" y="20" width="40" height="40" rx="8" fill="#ff00cc" filter="url(#glow)" />
  <rect x="60" y="60" width="40" height="40" rx="8" fill="#fff700" filter="url(#glow)" />
  <!-- More blocks for style -->
  <rect x="20" y="120" width="40" height="40" rx="8" fill="#00ffe7" filter="url(#glow)" />
  <rect x="60" y="120" width="40" height="40" rx="8" fill="#fff700" filter="url(#glow)" />
  <rect x="100" y="120" width="40" height="40" rx="8" fill="#ff00cc" filter="url(#glow)" />
  <rect x="140" y="120" width="40" height="40" rx="8" fill="#00ffe7" filter="url(#glow)" />
  <rect x="60" y="160" width="40" height="40" rx="8" fill="#fff700" filter="url(#glow)" />
  <rect x="100" y="200" width="40" height="40" rx="8" fill="#ff00cc" filter="url(#glow)" />
  <!-- Glowing "TETRIS" text -->
  <text x="50%" y="110" text-anchor="middle" font-size="36" font-family="monospace" fill="#fff" filter="url(#glow)">TETRIS</text>
</svg>
