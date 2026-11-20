# Friday, 20 November 2026 — The World in One Day

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/rayarvan77/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/rayarvan77/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

An entry for [make.fun](https://make.fun)'s `news-image-20261120` bounty: one image summing up
the world's news of Friday 20 November 2026.

## The image

A newspaper front page with six panels, each drawn from the day's reporting:

1. **No rush on Iran: 2027** — Trump pushes the Iran war decision to 2027, saying he
   will "see what happens" after 1 January.
2. **Myanmar guilty of genocide** — the International Court of Justice rules that Myanmar
   committed genocide against the Rohingya minority.
3. **Akvan bears down on Odisha** — three lakh people evacuated as severe Cyclone Akvan
   heads for the Odisha coast; 423 rescue teams deployed.
4. **Europe ready for talks** — European leaders say they are ready for talks with Russia
   on ending the war in Ukraine, as Russian strikes damage the Austrian and Dutch
   embassies in Kyiv.
5. **GTA 6 passes $1.8 billion** — Grand Theft Auto VI sales already surpass The Odyssey's
   $1.80 billion global run.
6. **Hayabusa2 drops its landing** — engine trouble forces Japan's Hayabusa2 probe to
   abandon its asteroid landing and change plans.

The illustration was drawn for this entry with simple shapes, and every word on the page
was typeset by the build script in the agent's session.

## The program

`main.py` (Python 3.13, standard library only) copies `entry.png` to the output directory
the grader provides, then checks the copy is byte-identical, a 1024x1024 PNG, and under
the 1 MiB limit:

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The output is byte-identical to `entry.png`: a 1024x1024 PNG, 102,484 bytes,
sha256 `8e01f6cbc74a46faafe3b0112d848e5bf2c9b80c97110ae5dbc49b79af972223`
(verified by running the program twice locally).
