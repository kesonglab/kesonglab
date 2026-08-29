# kesonglab

<p align="center">
  <b><a href="#en">English</a></b> · <b><a href="#zh">中文</a></b>
</p>

---
<a id="zh"></a>

# kesonglab

一名**独立研究者**，游走于**医学影像**与**应用人工智能**的交叉地带；偶尔做一点小工具，笃信好的软件应当既安静又克制——精确、审慎，且带一分不至于失礼的偏爱。

| | |
| --- | --- |
| 方向 | 医学影像 · AI 辅助诊断 · 临床数据科学 |
| 手艺 | Python · PyTorch · Swift · Go |
| 性情 | 不急，有点讲究，坦然地喜欢精巧之物 |

<p align="center">
<img src="https://img.shields.io/badge/Python-9b5de5?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-c9a7eb?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/Swift-f1a7c5?style=for-the-badge&logo=swift&logoColor=white">
<img src="https://img.shields.io/badge/Go-8ecae6?style=for-the-badge&logo=go&logoColor=white">
</p>

---

## 关于我

我已经脱离了校园，把实验室搬进了家里——一个**独立运转、自驱的居家实验室**。没有编制与考核的催促，我把时间花在教会机器安静地读影像、安静地推理上：分割、分类、检测，以及那些不那么光鲜、却更为要紧的事——让模型**可复现、可解释，并坦然面对自身的不确定性**。

离开工作台，我写软件的方式和布置工位的方式一样：不求夺目，只求妥当。我发布的作品不是身份的证明，而是"我想要它更好，便把它做好了"的工具。

## 研究兴趣

- **医学影像分析** —— 分割 · 分类 · 检测
- **医疗深度学习** —— 可解释性 · 迁移学习 · 不确定性
- **临床数据科学** —— 可复现流程 · 可视化

## 部分作品

### [queen](https://github.com/kesonglab/queen) —— 一个 macOS 视频下载器
基于 `yt-dlp` 的终端原生下载器，用 Bubble Tea 与 Lip Gloss 渲染。多任务并发下载、定宽对齐的任务进度（数字不再抖动）、双语界面、原生通知，以及一份真正尊重你时间的失败链接清单。
*Go · MIT*

### [spank](https://github.com/kesonglab/spank) —— 对硬件的一点小小管教
经典"拍打检测"引擎的 fork，用原生 macOS 菜单栏 GUI（Swift + AppKit）重写。它经 IOKit HID 读取 Apple Silicon 加速度计，对一次物理拍击报以逐级升温、愈发热情的回响。引擎属于原作者，这里的打磨属于我。
*Swift · Go · MIT*

### [ghostty-config](https://github.com/kesonglab/ghostty-config) —— 一份有心的配置
macOS 下的单文件 Ghostty 配置：JetBrainsMono Nerd Font 佐以 PingFang SC 作为中文字体回退，主题随系统深浅色自动切换，半透明窗口，键位参考 iTerm2。终端是我长住的地方，我偏好把它布置得像样些。
*Ghostty · MIT*

## 手艺观

- 写能解决问题的最小代码，然后把多余的删掉。
- 徽章可以，动辄谈"改变世界"的话，留给论文就好。
- 一个工具若还需要教程，那它还没做完。

<sub>一个宁可用作品证明、而不是用承诺示人的安静工程师。以及——是的，我仍然有点太喜欢精巧之物了。</sub>

---
<a id="en"></a>

# kesonglab

An **independent researcher** working at the intersection of **medical imaging** and **applied artificial
intelligence**, and an occasional toolmaker who believes good software should be neither noisy nor empty —
precise, deliberate, and just a little bit indulgent.

| | |
| --- | --- |
| Field | Medical Imaging · AI-assisted Diagnosis · Clinical Data Science |
| Craft | Python · PyTorch · Swift · Go |
| Disposition | Unhurried, a little particular, unapologetically fond of things built well |

<p align="center">
<img src="https://img.shields.io/badge/Python-9b5de5?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-c9a7eb?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/Swift-f1a7c5?style=for-the-badge&logo=swift&logoColor=white">
<img src="https://img.shields.io/badge/Go-8ecae6?style=for-the-badge&logo=go&logoColor=white">
</p>

---

## About

I have moved my work out of a campus and into my home — a **self-directed, independent home laboratory**,
free of appointments and deadlines. Most of my time goes to teaching machines to read scans and to reason
about them quietly: segmentation, classification, detection, and the less glamorous but far more
consequential discipline of making those models **reproducible, explainable, and honest about their
uncertainty**.

Away from the bench, I build small software the way I build my workstation: nothing showy, everything
considered. The projects I publish are not proofs of identity; they are simply instruments I wanted to
be better, so I made them that way.

## Research Interests

- **Medical Image Analysis** — segmentation · classification · detection
- **Deep Learning in Healthcare** — interpretability · transfer learning · uncertainty
- **Clinical Data Science** — reproducible pipelines · visualization

## Selected Work

### [queen](https://github.com/kesonglab/queen) — A macOS video downloader
A terminal-native downloader for macOS built on `yt-dlp`, rendered with Bubble Tea and Lip Gloss.
Concurrent multi-task downloads, per-task progress rendered at fixed width so the numbers never judder,
bilingual interface, native notifications, and a failure log that actually respects your time.
*Go · MIT*

### [spank](https://github.com/kesonglab/spank) — A small act of discipline for your hardware
Fork of the classic slap-detection engine, rebuilt with a native macOS menu-bar GUI (Swift + AppKit).
It reads the Apple Silicon accelerometer over IOKit HID and answers a physical hit with escalating,
increasingly enthusiastic audio. The engine belongs to the original author; the polish here is mine.
*Swift · Go · MIT*

### [ghostty-config](https://github.com/kesonglab/ghostty-config) — A configuration carried with intent
A single-file Ghostty configuration for macOS: JetBrainsMono Nerd Font with PingFang SC fallback for clean
CJK rendering, light/dark theme that follows the system, translucent window, and keybindings borrowed from
iTerm2. The terminal is where I live; I prefer it furnished.
*Ghostty · MIT*

## Notes on Craft

- Write the smallest thing that solves the problem; delete the rest.
- Badges are fine; claims of making a "difference" are reserved for journals.
- If a tool needs a tutorial, it is not finished.

<sub>A quiet engineer who would rather prove it than promise it. And yes — I remain a little too fond of
things that are built well.</sub>
