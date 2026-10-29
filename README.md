# MusicGan Web — Official Landing Page & Simulator

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FIlhamRichie%2FMusicGan-Web)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](LICENSE)
[![Tech](https://img.shields.io/badge/Stack-Vanilla%20HTML5%20%2F%20CSS3%20%2F%20ES6-E34F26?style=flat-square&logo=html5)](index.html)
[![Aesthetic](https://img.shields.io/badge/Design-Anti--Slop%20Dark%20Obsidian-10b981?style=flat-square)](index.html)
[![Desktop App](https://img.shields.io/badge/Desktop%20Repo-MusicGan--Desktop-blue?style=flat-square&logo=github)](https://github.com/IlhamRichie/MusicGan-Desktop)

The official high-performance showcase and distribution landing page for **[MusicGan](https://github.com/IlhamRichie/MusicGan-Desktop)** — the ultra-lightweight Apple Dynamic Island for Windows 10 & 11.

---

## Highlights & Interactive Architecture

- **Zero-Dependency Native Stack:**
  Built with pure HTML5, vanilla CSS3, and ES6 JavaScript. No bundlers, no heavy frameworks, and zero build step required.
- **Strict Anti-Slop UI Standard:**
  Designed with disciplined typography (`Bahnschrift` & `Inter`), zero emojis in copy/buttons, handcrafted vector SVG glyphs, and high-contrast accessibility.
- **Interactive System Simulator:**
  Features a live, client-side replica of the MusicGan Dynamic Island right in the browser:
  - **Fluid Width Auto-Sizing:** The island dynamically adjusts its horizontal dimensions to match each line of synchronized lyrics in real-time.
  - **Live Equalizer Bars:** Real-time waveform audio animations.
  - **Hover-to-Expand Glass Card:** Smooth transition revealing album artwork, track scrubbers, and playback controls.
  - **7-Color Accent Switcher:** Switch between Emerald, Cyan, Violet, Rose, Amber, Blue, and Slate presets, instantly updating the ambient canvas glow and interface accents.
- **Technical Architecture Matrix:**
  Interactive telemetry tabs comparing native C# DirectX/WPF footprint against legacy Electron wrappers.
- **Direct Asset Distribution:**
  Hosts standalone downloads (`MusicGan.exe` & `MusicGan-v1.2.zip`) directly for instant zero-friction delivery.

---

## One-Click Deployment on Vercel

This repository is optimized for instant deployment on **Vercel**:

1. Log into your [Vercel Dashboard](https://vercel.com/).
2. Click **Add New** > **Project**.
3. Import `IlhamRichie/MusicGan-Web`.
4. Keep the Framework Preset as **Other** (Root directory: `./`).
5. Click **Deploy**.

Your landing page will be instantly live with global edge caching and free SSL.

---

## Local Development & Preview

Because this project is zero-dependency, you can run and preview it immediately:

```bash
# Option A: Open directly in your default browser
start index.html

# Option B: Run a quick local HTTP server
npx serve .
# or
python -m http.server 8080
```

---

## File Structure

```
├── index.html           # Complete single-page landing site with interactive simulator
├── app.ico              # Multi-resolution application brand icon
├── MusicGan.exe         # Compiled 90 KB standalone Windows binary
├── MusicGan-v1.2.zip    # Compressed distribution package for direct downloads
├── README.md            # Repository documentation
└── LICENSE              # MIT License
```

---

## Related Repositories

- 🖥️ **Desktop Client:** [IlhamRichie/MusicGan-Desktop](https://github.com/IlhamRichie/MusicGan-Desktop) — The core C# WPF Dynamic Island application.

---

## Creator & Support

Crafted with passion by **[Ilham Richie](https://richie-portfolio.vercel.app/#home)**.

- ☕ **Support & Amal Jariyah via Saweria:** [saweria.co/rigannnnn](https://saweria.co/rigannnnn)
- 📷 **Instagram:** [@maachigan](https://www.instagram.com/maachigan)
- 🌐 **Portfolio:** [richie-portfolio.vercel.app](https://richie-portfolio.vercel.app/#home)

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
