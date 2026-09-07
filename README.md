# Yr7 ICT Online Tasks 2026

Self-marking, self-contained tasks for Year 7 ICT — set for study days and other
times the class is not in a normal lesson. Each task is one static HTML file with
an embedded video, lots of questions, instant feedback, and a results summary the
student can screenshot, copy or print.

**Live site:** https://wanly20.github.io/Yr7_ict_online_tasks_2026/

## Tasks

| # | Task | Media |
|---|------|-------|
| 1 | The History of the Spreadsheet | Dan Bricklin TED talk (YouTube embed) |

## Assets

`assets/` holds images used by tasks. Credits are shown in each task's footer.
Current files (all resized/compressed):

- `visicalc-1979.png` — VisiCalc screenshot, public domain (Wikimedia Commons).
- `apple-ii.jpg` — Apple II, Rama & Musée Bolo, CC BY-SA 2.0 FR (background removed).
- `dan-bricklin.jpg` — Dan Bricklin portrait, Luca Lucarini, CC BY-SA 3.0.
- `acoustic-coupler.jpg` — acoustic coupler, OlivierBerger, CC BY-SA 3.0.
- `vt100-terminal.jpg` — DEC VT100 terminal, Jason Scott, CC BY 2.0.
- `google-sheets-today.png` — Google Sheets screenshot (own).

Keep images small (resize to ~1000px, compress) — students open these from home.

## Adding a task

1. Drop `NN_<slug>.html` into the repo root (self-contained — Tailwind via CDN is fine).
2. Add a link row to `index.html` and a row to the table above.
3. Commit and push — GitHub Pages redeploys automatically.

## Notes

- Answers are saved in the student's browser (`localStorage`); no data leaves the device.
- Nothing is submitted anywhere — the student reports their own score.
