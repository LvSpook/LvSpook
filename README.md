<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="banner-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="banner.svg">
  <img src="banner.svg" alt="LvSpook — Windows desktop tools, mostly in Rust" width="100%">
</picture>

<br>

[![Windows](https://img.shields.io/badge/PLATFORM-WINDOWS-000000?style=for-the-badge&labelColor=000000&logo=windows&logoColor=ff1f3d&color=1a0508)](https://github.com/LvSpook?tab=repositories)
[![Rust](https://img.shields.io/badge/PRIMARY-RUST-000000?style=for-the-badge&labelColor=000000&logo=rust&logoColor=ff1f3d&color=1a0508)](https://www.rust-lang.org)
[![Status](https://img.shields.io/badge/STATUS-BUILDING-000000?style=for-the-badge&labelColor=000000&color=1a0508&logoColor=ff1f3d)](#)

</div>

---

```console
LvSpook@windows:~$ whoami
>> solo dev. small tools. zero bloat.
LvSpook@windows:~$ cat manifesto.txt
>> if it takes more than a second to open, it's already wrong.
```

### Hey — I'm LvSpook 👋

I build **small, focused desktop apps for Windows** — things that should exist,
weigh almost nothing, and stay out of the way. Mostly Rust against native
Windows APIs instead of a browser wearing a trench coat.

I care about the parts nobody demos: a binary that opens instantly, settings
that never get lost, an installer that doesn't demand admin rights, and an
uninstall that actually removes the app.

---

## ⚡ Currently building

<table>
<tr>
<td width="50%" valign="top">

**Shipping**
- Green Timer — overlay timer for Windows
- Native tray apps with live theming
- Release pipelines on GitHub Actions

</td>
<td width="50%" valign="top">

**Principles**
- Small binaries, fast cold starts
- No admin rights, no telemetry
- Settings that survive updates
- Honest docs about how it's built

</td>
</tr>
</table>

---

## 🔴 Featured

<div align="center">

### Green Timer

**A frameless, always-on-top timer overlay for Windows.**
Count up, count down, run a Pomodoro, or aim at a specific time — over any
window, without stealing clicks.

<a href="https://github.com/LvSpook/Green-Timer">
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/LvSpook/Green-Timer/main/docs/banner-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LvSpook/Green-Timer/main/docs/banner.svg">
  <img src="https://raw.githubusercontent.com/LvSpook/Green-Timer/main/docs/banner.svg" alt="Green Timer banner" width="100%">
</picture>
</a>

[![Source](https://img.shields.io/badge/SOURCE-GREEN--TIMER-ff1f3d?style=flat-square&labelColor=000000&logo=github&logoColor=ff1f3d)](https://github.com/LvSpook/Green-Timer)
[![Docs](https://img.shields.io/badge/DOCS-LIVE-ff1f3d?style=flat-square&labelColor=000000&logo=githubpages&logoColor=ff1f3d)](https://lvspook.github.io/Green-Timer/)
[![Release](https://img.shields.io/github/v/release/LvSpook/Green-Timer?include_prereleases&label=RELEASE&color=ff1f3d&labelColor=000000&style=flat-square)](https://github.com/LvSpook/Green-Timer/releases)
[![License](https://img.shields.io/badge/LICENSE-MIT-ff1f3d?style=flat-square&labelColor=000000)](https://github.com/LvSpook/Green-Timer/blob/main/LICENSE)

</div>

<table>
<tr>
<td width="50%" valign="top">

**Timer modes**
- Count Up · Countdown · Clock
- Pomodoro · Interval/HIIT · Target Time

</td>
<td width="50%" valign="top">

**Display styles**
- Text · Arc · Bar · Fluid · Sprite

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Look and feel**
- Seven themes plus a custom builder
- Gradients, text shadows, warning pulses
- Optional acrylic backdrop

</td>
<td width="50%" valign="top">

**Behaviour**
- Global hotkeys by physical key
- Tray, profiles, per-app auto-switch
- Lap history with CSV export

</td>
</tr>
</table>

> [!WARNING]
> Green Timer is a work in progress and ships as pre-releases. The UI and file
> formats may still change between versions.

---

## 🧰 Stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=ff1f3d)
![Windows API](https://img.shields.io/badge/Win32-000000?style=for-the-badge&logo=windows&logoColor=ff1f3d)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=ff1f3d)
![Actions](https://img.shields.io/badge/Actions-000000?style=for-the-badge&logo=githubactions&logoColor=ff1f3d)
![PowerShell](https://img.shields.io/badge/PowerShell-000000?style=for-the-badge&logo=powershell&logoColor=ff1f3d)
![Inno Setup](https://img.shields.io/badge/Inno%20Setup-000000?style=for-the-badge&logo=windows&logoColor=ff1f3d)

</div>

---

## 📊 The numbers

<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=LvSpook&show_icons=true&hide_title=true&hide_border=true&bg_color=ffffff&title_color=c1121f&icon_color=c1121f&text_color=2a1013&rank_icon=github">
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=LvSpook&show_icons=true&hide_title=true&hide_border=true&bg_color=000000&title_color=ff1f3d&icon_color=ff1f3d&text_color=f5d7da&rank_icon=github">
  <img src="https://github-readme-stats.vercel.app/api?username=LvSpook&show_icons=true&hide_title=true&hide_border=true&bg_color=000000&title_color=ff1f3d&icon_color=ff1f3d&text_color=f5d7da&rank_icon=github" alt="GitHub stats" height="165">
</picture>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=LvSpook&layout=compact&hide_border=true&bg_color=ffffff&title_color=c1121f&text_color=2a1013&langs_count=6">
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=LvSpook&layout=compact&hide_border=true&bg_color=000000&title_color=ff1f3d&text_color=f5d7da&langs_count=6">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LvSpook&layout=compact&hide_border=true&bg_color=000000&title_color=ff1f3d&text_color=f5d7da&langs_count=6" alt="Top languages" height="165">
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=LvSpook&hide_border=true&background=ffffff&stroke=f3dcdf&ring=c1121f&fire=e11d2e&currStreakNum=a11322&sideNums=0a0a0b&currStreakLabel=c1121f&sideLabels=8c5a60&dates=8c5a60">
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=LvSpook&hide_border=true&background=000000&stroke=2a0a0f&ring=ff1f3d&fire=ff5c74&currStreakNum=ff5c74&sideNums=f5d7da&currStreakLabel=ff1f3d&sideLabels=b06870&dates=b06870">
  <img src="https://streak-stats.demolab.com?user=LvSpook&hide_border=true&background=000000&stroke=2a0a0f&ring=ff1f3d&fire=ff5c74&currStreakNum=ff5c74&sideNums=f5d7da&currStreakLabel=ff1f3d&sideLabels=b06870&dates=b06870" alt="Contribution streak" height="165">
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=LvSpook&bg_color=ffffff&color=2a1013&line=c1121f&point=a11322&area=true&area_color=c1121f&hide_border=true">
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=LvSpook&bg_color=000000&color=f5d7da&line=ff1f3d&point=ff5c74&area=true&area_color=ff1f3d&hide_border=true">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=LvSpook&bg_color=000000&color=f5d7da&line=ff1f3d&point=ff5c74&area=true&area_color=ff1f3d&hide_border=true" alt="Contribution activity" width="100%">
</picture>

</div>

---

## 🤖 How this is built

Some of my code, docs and release tooling are written with the help of an AI
coding assistant, under my direction and review. I say so because you should
know how the software you install was made. It is not an official product of any
AI company and is not endorsed by one. AI-assisted code can contain mistakes a
human would not have made — tests and manual checks reduce that risk but cannot
remove it.

---

<div align="center">

<sub>Windows · Rust · MIT · built in small pieces</sub>

</div>
