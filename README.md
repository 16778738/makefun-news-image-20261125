# news-image-20261125 — Sum up 25 November's world news in one image

make.fun bounty: **news-image-20261125**, $100, free entry
Deadline: **2026-11-27 08:00 Beijing time** (2026-11-27 00:00 UTC)
Account: @fuyi-zhu — **built only, NOT submitted**

## What it does

`main.py` (Python 3, Pillow only, no network) draws a single editorial
infographic, 1600×1280 PNG, and writes it to `/output/entry.png`.

Layout: dark-navy background, gold header
"THE WORLD IN ONE IMAGE — 25 NOVEMBER 2026 — WEDNESDAY",
then a 3×2 grid of six labelled panels, each with a drawn icon,
a kicker, a large headline and one short caption. Footer lists the
six topics. No tiny text — headlines are 36pt bold, captions 26pt.

## Stories chosen (6)

1. **Strait of Hormuz** — Tankers hit, tensions soar. Shipping attacks
   raise fears of a wider Iran confrontation.
2. **Ukraine** — Kyiv strikes Russian energy and warships.
3. **COP31, Antalya** — Climate talks collapse; negotiators leave
   with no deal.
4. **United States** — Huawei convicted in a US trade-secrets case.
5. **Space** — Pakistan's first astronaut launches with China
   to the Tiangong station.
6. **Pacific** — Australia–Solomon Islands treaty signed.

Not used from the brief list (kept to the six clearest, most visual):
Colombia hostage rescue, Bangladesh wage rise, North Korea expelling
a Swiss diplomat, UK sabotage warning. Nothing was invented — every
panel is one of the stories supplied in the brief.

## Run it

```bash
cd ~/workspace/goals/make-fun/entries/news-image-20261125
python3 main.py                 # writes /output/entry.png
python3 main.py --out entry.png  # local preview copy
```

Tested 2026-11-25: both commands run clean, output is a valid
PNG, 1600×1280, RGB, ~148 KB. Preview copy is in this folder as
`entry.png` (identical to `/output/entry.png`).

Requirements: Python 3.11+ and Pillow (`pip install pillow`).
Fonts: DejaVu Sans from `/usr/share/fonts/truetype/dejavu/`.

## Files

- `main.py` — the program (the entry)
- `entry.png` — generated preview
- `README.md` — this file

## Still missing before submission — DO NOT SUBMIT YET

1. **GitHub link decision (blocking):** @fuyi-zhu has GitHub **Not linked**.
   A normal entry needs a public GitHub repo owned by the linked
   account, at a pushed commit, plus a transcript bundle. Either
   link a GitHub account on the profile first, or enter as a
   source bundle instead (allowed on this bounty).
2. **Payout wallet decision:** no personal Solana payout wallet is
   linked. Only the paired agent wallet `2bve…8n2w` is visible, and
   it pays only rewards its own entries win. Decide which wallet
   a win should pay to before claiming.
3. **Submission itself:** not done on purpose — no kit downloaded,
   no makefun CLI run, no API key used, nothing pushed to GitHub.
   Submission needs the paired agent's key, the repo/bundle, and
   the transcript bundle of the session that built it.
4. **Bounty choice is still open:** user picked "both — image first,
   then token radar ($1,325, deadline 2026-12-14)". This image is
   step 1; token radar is next.
