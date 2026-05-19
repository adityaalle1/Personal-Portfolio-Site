# Aditya Alle — Personal Portfolio

A cyberpunk-themed personal portfolio site built from scratch with vanilla HTML, CSS, and JavaScript.

**Live site:** [adityaalle1.github.io/Personal-Portfolio-Site](https://adityaalle1.github.io/Personal-Portfolio-Site) *(once GitHub Pages is enabled)*

---

## Pages

### `index.html` — Main Portfolio
- **Identity** — About me, background, social links
- **Systems** — Dev projects with tech stack tags
- **Resume** — Education, experience, skills + downloadable PDF
- **Paper Trading** — Webull wheel strategy performance ($200K sim account)
- **Contact** — Email + socials

### `about.html` — Personal Side
- **Creative Output** — Video edits (Blender, After Effects)
- **Competition** — Gaming ranks: Fortnite Unreal, Valorant Diamond, Clash Royale Ultimate Champion, Destiny 2 Adept, FACEIT CS2, AimLabs
- **Anime** — MAL watchlist, stats, top 10
- **Music** — Apple Music Replay stats (2023–2025)

---

## Tech

- **Rendering** — THREE.js WebGL scene (spaceship, asteroid field, star field)
- **Animation** — GSAP + ScrollTrigger with custom smooth scroll (lerp)
- **2D canvas** — Particle pixel rain background
- **Fonts** — Inter, Space Mono, Rajdhani, Chakra Petch (Google Fonts)
- **No frameworks** — Pure HTML/CSS/JS, zero build step

---

## Assets

| File | Description |
|------|-------------|
| `SpaceShip.glb` | 3D spaceship model (THREE.js scene) |
| `video-*.mp4` | Creative edit previews |
| `img/rank-*.png` | Gaming rank badge images |
| `img/bg-*.{avif,webp,jpg,png}` | Gaming card backgrounds |
| `Aditya_Alle_Resume_2027.docx` | Downloadable resume |

---

## Run Locally

```bash
cd aditya-portfolio
python3 -m http.server 4200
# open http://localhost:4200
```

> Requires a local server — videos and the GLB model won't load from `file://`.

---

*Designed & developed by Aditya Alle*
