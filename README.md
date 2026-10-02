<div align="center">

# kesonglab

*I read quiet images, and teach small machines to read them too.*

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

I'm a doctor in the imaging department, mostly. Now and then I build a small tool, or train a model
on medical images. Small work, done slowly, and checked against the evidence.

## Selected work

### [queen](https://github.com/kesonglab/queen) — a macOS video downloader

A terminal-native downloader built on `yt-dlp` and rendered with Bubble Tea and Lip Gloss. Concurrent
downloads, per-task progress locked to a fixed width so the numbers never judder, a bilingual interface,
native notifications, and a failure log that actually respects your time.
*Go · MIT*

### [ghostty-config](https://github.com/kesonglab/ghostty-config) — a configuration kept with intent

A single-file Ghostty config for macOS: JetBrainsMono Nerd Font with a PingFang SC fallback for clean CJK
rendering, a theme that follows the system, a translucent window, and iTerm2-flavored keybindings. The
terminal is where I live; I'd rather not live somewhere shabby. Maintained with CI that validates the
config on every change.
*Ghostty · MIT*

## Code review

Things I recently took from idea to merge — branch, review, CI, homing in on the details, then a clean
squash. Every step green before it moved on.

- `ghostty-config` **#2** — `feat:` default working directory for new windows. `+validate-config` clean on both macOS runners, then merged.
- `ghostty-config` **#3** — `docs:` synced README & CHANGELOG to match; markdownlint, zero warnings.
- `ghostty-config` **v0.2.0** — cut a release whose notes came out of the CHANGELOG, no drift.
- *Workflow discipline:* branch → PR → CI green → squash → prune, every time. Config + docs ship in one atomic PR.

Reviews offered upstream — code handed back with the polish applied, not just a verdict:

- [`Project-MONAI/MONAI` **#9134**](https://github.com/Project-MONAI/MONAI/pull/9134) — approved a MeanIoU `ignore_index` fix after reproducing the old channel-wipe path (class-0 IoU ≈0.67 on the ignored voxel → 1.0 after spatial masking, matching Dice); suggested an `include_background=False` assertion to lock the mask-vs-channel interaction.
- [`averygan/reclip` **#79**](https://github.com/averygan/reclip/pull/79) — reviewed a yt-dlp `--` separator-only injection fix against yt-dlp 2026.08.19; confirmed all three call sites, and pointed out it is a weaker subset of #58 (no `is_safe_url` early reject).
- [`spotDL/spotify-downloader` **#2795**](https://github.com/spotDL/spotify-downloader/pull/2795) — reviewed a YouTube Music locale-fallback retry (`en`/`de` client cycling); flagged the silent `de→en` default flip, the duplicated third attempt, and the missing mock regression test.

## On making

- Write the smallest thing that solves the problem, then delete what remains.
- Badges are welcome; declarations of "impact" belong in journals.
- If a tool needs a tutorial, it isn't finished.

---

<div align="center">
*Quiet, precise, and immune to becoming boring.*

*Made with care, and a touch of indulgence, by kesonglab.*
</div>
