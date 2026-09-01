<div align="center">

# kesonglab

*machine-whisperer · instrument-maker · a little too fond of beautiful things*

[![Python](https://img.shields.io/badge/Python-9b5de5?style=for-the-badge&logo=python&logoColor=white)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-c9a7eb?style=for-the-badge&logo=pytorch&logoColor=white)]()
[![Go](https://img.shields.io/badge/Go-8ecae6?style=for-the-badge&logo=go&logoColor=white)]()
[![Swift](https://img.shields.io/badge/Swift-f1a7c5?style=for-the-badge&logo=swift&logoColor=white)]()

[![Ghostty](https://img.shields.io/badge/Ghostty-efe1c6?style=for-the-badge&logo=terminal&logoColor=white)]()
[![BubbleTea](https://img.shields.io/badge/BubbleTea-9b5de5?style=for-the-badge&logo=go&logoColor=white)]()
[![LipGloss](https://img.shields.io/badge/LipGloss-577590?style=for-the-badge&logo=go&logoColor=white)]()
[![macOS](https://img.shields.io/badge/macOS-577590?style=for-the-badge&logo=apple&logoColor=white)]()

</div>

---

## About me

I work at the quieter end of medicine — teaching machines to read scans, and to be honest about the
parts they get wrong. No campus, no tenure clock, no committee to satisfy: just a home laboratory I run
myself, where the work answers to no one but the evidence.

Segmentation, classification, detection, and the unglamorous discipline underneath all of them —
making models **reproducible, explainable, and willing to admit their own uncertainty**. That is the
part I actually care about.

When I'm not at the bench, I build small software the way I furnish a room: nothing loud, everything
intentional. The things I publish aren't badges of identity. They're just tools I wanted to be better,
so I made them that way.

## What I reach for

- **Medical image analysis** — segmentation · classification · detection
- **Deep learning for healthcare** — interpretability · transfer learning · uncertainty
- **Clinical data science** — reproducible pipelines · visualization
- **Terminal-native tooling** — Go TUI, sensors, and small automation that disappears into the workflow

## Selected work

### [queen](https://github.com/kesonglab/queen) — a macOS video downloader
A terminal-native downloader built on `yt-dlp` and rendered with Bubble Tea and Lip Gloss. Concurrent
downloads, per-task progress locked to a fixed width so the numbers never judder, a bilingual interface,
native notifications, and a failure log that actually respects your time.
*Go · MIT*

### [spank](https://github.com/kesonglab/spank) — a small act of discipline for your hardware
A fork of the classic slap-detection engine, rebuilt with a native macOS menu-bar GUI (Swift + AppKit,
with a Go engine). It reads the Apple Silicon accelerometer over IOKit HID and answers a physical hit
with escalating, increasingly enthusiastic audio. The engine is the original author's; the polish is mine.
*Swift · Go · MIT*

### [ghostty-config](https://github.com/kesonglab/ghostty-config) — a configuration kept with intent
A single-file Ghostty config for macOS: JetBrainsMono Nerd Font with a PingFang SC fallback for clean CJK
rendering, a theme that follows the system, a translucent window, and iTerm2-flavored keybindings. The
terminal is where I live; I'd rather not live somewhere shabby. Maintained with CI that validates the
config on every change.
*Ghostty · MIT*

## Open source

I build things in the open and I send fixes back upstream when the tools I use let me down. My
[contribution history](https://github.com/kesonglab?tab=overview) is the
honest record of that; the work that currently matters most is on
[hister](https://github.com/asciimoo/hister), a private search engine — see
[PR #712](https://github.com/asciimoo/hister/pull/712) making the similarity threshold adjustable when
a semantic search returns no results.

If a tool is worth using, it's worth leaving a little better than I found it.

## Code review · 近期审查与协作

Things I recently took from idea to merge — branch, review, CI, homing in on the details, then a clean
squash. Every step green before it moved on.

- `ghostty-config` **#2** — `feat:` default working directory for new windows. `+validate-config` clean on both macOS runners, then merged.
- `ghostty-config` **#3** — `docs:` synced README & CHANGELOG to match; markdownlint, zero warnings.
- `ghostty-config` **v0.2.0** — cut a release whose notes came out of the CHANGELOG, no drift.
- *Workflow discipline:* branch → PR → CI green → squash → prune, every time. Config + docs ship in one atomic PR.

## On making

- Write the smallest thing that solves the problem, then delete what remains.
- Badges are welcome; declarations of "impact" belong in journals.
- If a tool needs a tutorial, it isn't finished.

---

<div align="center">
*Quiet, precise, and immune to becoming boring.*

*Made with care, and a touch of indulgence, by kesonglab.*
</div>