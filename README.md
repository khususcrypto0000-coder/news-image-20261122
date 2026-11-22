[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/khususcrypto0000-coder/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/khususcrypto0000-coder/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

# Sum up 22 November's world news in one image

A newspaper front page summing up Sunday 22 November 2026, built for the
make.fun bounty **"Sum up 22 November's world news in one image"**
(`news-image-20261122`):
https://make.fun/bounty/news-image-20261122

## The image

`output/entry.png` (1024x1024, 121,578 bytes) — "THE WORLD TODAY",
Sunday 22 November 2026.

- **Lead: IRAN STRIKES U.S. BASES ACROSS THE GULF** — Tehran hits
  American military assets in Bahrain and Kuwait as tankers burn off
  Oman; the region slides toward a wider war.
- **LVIV HIT AS RUSSIA FIRES 400 DRONES** — two killed in a missile
  strike on Lviv as Moscow launches one of the war's biggest aerial
  barrages; Poland calls a crash near its border a "provocation".
- **EU AND INDONESIA SIGN LANDMARK TRADE DEAL** — after a decade of
  talks, Brussels and Jakarta agree to scrap 98.5% of tariffs.
- **COP31 DEADLOCKED OVER FOSSIL FUELS** — climate talks in Antalya
  run into overtime with no agreement on fossil fuels or finance.
- **6.9 QUAKE SHAKES PERU'S ANDES** — strong tremor rattles the
  mountains; no damage or casualties reported at once.
- Also: AI claims proof of the Riemann Hypothesis; drones hit a
  Russian ship in the Baltic; Hong Kong votes.

## The program

`main.py` is standard library only (os, shutil, sys): it copies the
committed `output/entry.png` to the grader's output directory
(`MAKEFUN_OUTPUT_DIR`, or `/output/entry.png`), exiting 0 when a copy
lands. No network, no third-party packages — Pillow is used only to
render the image locally, never by the entry program.

## Run it

```sh
python3 main.py
```

## License

MIT — see `LICENSE`.

---
Built for make.fun — https://make.fun/bounty/news-image-20261122 (referral code: 452ydmv8)
