<div align="center">

<img src="https://avatars.githubusercontent.com/u/262773687?v=4" width="96" height="96" alt="Sahen" />

# Hi, I'm Sahen

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=58A6FF&center=true&vCenter=true&width=440&lines=I+build+fast+tools+in+Rust.;Speed+is+proven+with+numbers.;From+Osaka%2C+Japan)](https://git.io/typing-svg)

**Student dev from Osaka, Japan. Rust-first. I prove speed with numbers, not adjectives.**

[![views](https://komarev.com/ghpvc/?username=sahenjp&color=blueviolet&style=flat)](https://github.com/sahenjp)
[![followers](https://img.shields.io/github/followers/sahenjp?label=Follow&style=for-the-badge)](https://github.com/sahenjp?tab=followers)
[![stars](https://img.shields.io/github/stars/sahenjp?label=Total%20Stars&style=for-the-badge)](https://github.com/sahenjp?tab=repositories)
[![blog](https://img.shields.io/badge/blog-sahen.site-79bda0?style=for-the-badge)](https://sahen.site)
[![X](https://img.shields.io/badge/X-%40sahenjpn-black?logo=x&style=for-the-badge)](https://x.com/sahenjpn)

[🌐 sahen.site](https://sahen.site) · [✉️ hello@sahen.site](mailto:hello@sahen.site) · [📦 All repos](https://github.com/sahenjp?tab=repositories)

</div>

---

## 🔥 Flagship: rdsh — 98x faster launcher for DeepSeek Harness

<div align="center">

[![stars](https://img.shields.io/github/stars/jimoto-no-llm/rustdsh?style=for-the-badge)](https://github.com/jimoto-no-llm/rustdsh)
[![release](https://img.shields.io/github/v/release/jimoto-no-llm/rustdsh?style=for-the-badge)](https://github.com/jimoto-no-llm/rustdsh/releases)
[![CI](https://img.shields.io/github/actions/workflow/status/jimoto-no-llm/rustdsh/ci.yml?label=CI&style=for-the-badge)](https://github.com/jimoto-no-llm/rustdsh/actions/workflows/ci.yml)

**Top contributor. Drop-in replacement for `dsh`. Native Rust, safe by default.**

|  | rdsh (Rust) | dsh (Node.js) |
|---|---|---|
| `--version` startup | **~0.90 ms** | ~88 ms |
| Peak memory | **~2.9 MB** | ~66 MB |
| Speedup | **~98x faster** | 1x |

<a href="https://github.com/jimoto-no-llm/rustdsh"><img src="https://github.com/jimoto-no-llm/rustdsh/raw/main/preview-intelligent-ui.png" width="720" alt="rdsh demo" /></a>

</div>

```sh
# 10 seconds to feel it
curl -fsSL https://github.com/jimoto-no-llm/rustdsh/releases/latest/download/install.sh | bash -s -- --from-release
rdsh --version && rdsh doctor
rdsh bench --n 5
```

- 🔄 **Zero migration:** every existing `dsh` command works as-is; unknown subcommands pass through
- ⚡ **Native utils:** `tokens / search / sessions / doctor / bench` without starting Node.js
- 🛡️ **Safe by default:** read-only mode never mutates; no credential auto-sync
- 📊 **Reproducible:** every number is re-measurable with `rdsh bench`

➡️ **[jimoto-no-llm/rustdsh](https://github.com/jimoto-no-llm/rustdsh)** — Stars / Issues / PRs welcome. Starが一番の励みです.

---

## 📦 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🔐 lvau — ⭐ 10

Secure-by-default file encryption in Rust. My signature work.

```sh
cargo install --git https://github.com/sahenjp/lvau
lvau encrypt file.txt -o file.lvau
```

`Rust / XChaCha20-Poly1305 / Argon2id / CLI+GUI`

[➡️ sahenjp/lvau](https://github.com/sahenjp/lvau)

</td>
<td width="50%" valign="top">

### 🎙️ auralis — real-time denoising

Real-time noise suppression for Windows 11. Audio never leaves your PC.

[⬇️ Download Windows build](https://huggingface.co/j-llm/Auralis/resolve/main/Auralis-Windows-x64.zip) → run `start-auralis.cmd`

`Rust / real-time inference / GUI / privacy`

[➡️ sahenjp/auralis](https://github.com/sahenjp/auralis)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏎️ solidcraft-perf

Pure-Rust parametric 3D CAD, measured fork. Speed / memory / binary size with repro harness.

`Rust / CAD / benchmarking / MCP`

[➡️ sahenjp/solidcraft-perf](https://github.com/sahenjp/solidcraft-perf)

</td>
<td width="50%" valign="top">

### 🧪 PatchArena / PolyDecomp

Repro benchmark runner for AI coding agents + polygon decomposition experiments.

`Rust / AI agents / reproducibility`

[➡️ sahenjp/PatchArena](https://github.com/sahenjp/PatchArena)

</td>
</tr>
</table>

> AI disclosure: Aegis ACBS and Nelo are mostly AI-assisted, and lvau is about half. Numbers and security-critical paths are human-verified.

---

## 🛠️ What I do

<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,ts,python,react,nodejs,deno,github,vscode&theme=dark" alt="stack" />
  <br />
  <sub><b>Measure → Reproduce → Ship.</b> Rust / TypeScript / Python / React / Node.js / Deno</sub>
</div>

---

## 📊 Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sahenjp&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahenjp&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="langs" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./activity/lifetime.dark.svg" />
  <img src="./activity/lifetime.light.svg" width="100%" alt="contribution history" />
</picture>

---

<details>
<summary>🎵 Now playing / More</summary>

<div align="center">
  <a href="https://spotify-github-profile.kittinanx.com/api/view?uid=3174zob3smqhorhqpincnu2rlvmq&redirect=true">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=3174zob3smqhorhqpincnu2rlvmq&cover_image=true&theme=novatorem&show_offline=true&background_color=0d1117&bar_color=1DB954&border_radius=16" width="360" alt="Spotify now playing" />
  </a>
</div>

</details>

<div align="center">
<sub>Osaka, Japan · <a href="https://sahen.site">sahen.site</a> · <a href="mailto:hello@sahen.site">hello@sahen.site</a> · ⭐ Starが一番の励みです</sub>
</div>