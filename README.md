# daily-light

A beautiful, offline-first screensaver that cycles through Quran verses, Bible verses, inspiring quotes, and fascinating facts — right in your browser.

---

## Features

- **Thousands of verses** — Full Quran (6,236 verses, Sahih International) and Bible (31,102 verses, KJV) available via opt-in download, cached locally after first fetch
- **Arabic + English Quran** — Display Arabic script, English translation, or both side by side
- **Inspiring quotes** — 260+ quotes from thinkers, scientists, poets, and leaders across history
- **Interesting facts** — 250+ facts spanning science, history, nature, space, geography, and more
- **3 themes** — Dark (starfield), Gradient (animated blobs), Minimal (clean/light)
- **Fully offline** — No external requests by default; data files are local
- **Privacy-first** — Optional full download is clearly labeled with which servers are contacted
- **Auto-hiding controls** — UI fades away after 3 seconds of inactivity for a distraction-free look
- **Keyboard shortcuts** — Navigate, pause, switch themes, and more without touching the mouse

---

## Getting Started

Just open `index.html` in any modern browser. No server, no install, no build step.

```sh
git clone https://github.com/XionDot/daily-light.git
cd daily-light
open index.html   # macOS
# or double-click index.html on any OS
```

To unlock the full verse library (~37k verses), click **Download Full Library** inside the settings panel. Data is fetched once and stored locally — no repeated downloads.

---

## Keyboard Shortcuts

| Key | Action |
| --- | ------ |
| `→` / `Space` | Next item |
| `←` | Previous item |
| `P` | Pause / Resume |
| `F` | Toggle fullscreen |
| `S` | Open settings |
| `?` / `H` | Show keyboard shortcuts |
| `1` / `2` / `3` | Switch theme |
| `Esc` | Close open panel |

---

## Project Structure

```text
daily-light/
├── index.html         — Main UI and all logic
├── data/
│   ├── bible.js       — KJV verses from all 66 books
│   ├── quran.js       — Sahih International verses from all 114 surahs (with Arabic)
│   ├── quotes.js      — 260+ quotes
│   └── facts.js       — 250+ facts
└── LICENSE
```

---

## Settings

- **Theme** — Dark / Gradient / Minimal
- **Interval** — How long each item is displayed (5–60 seconds)
- **Show** — Filter by category: All, Bible, Quran, Quotes, Facts
- **Quran Script** — Arabic only / Both / English only

---

## Support

If you find this useful, consider buying me a coffee:
[buymeacoffee.com/cr4ne](https://buymeacoffee.com/cr4ne)

---

## License

MIT — see [LICENSE](LICENSE)
