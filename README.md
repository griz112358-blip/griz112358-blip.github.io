# Resume · Haoran Tao (陶浩然)

Live site: https://griz112358-blip.github.io/

- `/` — 中文版
- `/en/` — English version
- `/resume-cn.pdf`, `/resume-en.pdf` — PDF downloads

Source lives in `~/resume/site` (and `~/resume/AI Agent开发版` for the source resumes).
Deployed via GitHub Pages (legacy build from `main`).

## Stack

Static HTML + one stylesheet (`style.css`) + inline vanilla JS:

- light / dark theme toggle (persisted in `localStorage`)
- scroll-progress bar
- section reveal-on-scroll (IntersectionObserver, with a `<noscript>` fallback)
- print stylesheet tuned for A4 (top bar and animations stripped)
