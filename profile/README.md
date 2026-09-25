<p align="center">
  <img src="https://raw.githubusercontent.com/oxide-terminal/oxide/main/assets/icon_1024.png" width="160" alt="Oxide icon — a corroded iron terminal prompt" />
</p>

<h1 align="center">Oxide Terminal</h1>

<p align="center">
  A native terminal emulator for macOS and Linux, written entirely in Rust.<br/>
  <em>Rust is iron oxide. It's a whole thing.</em>
</p>

<p align="center">
  <a href="https://oxideterminal.com">Website</a> ·
  <a href="https://oxideterminal.com/docs/">Docs</a> ·
  <a href="https://oxideterminal.com/changelog/">Changelog</a> ·
  <a href="https://oxideterminal.com/compare/">Compare</a> ·
  <a href="https://blog.oxideterminal.com">Blog</a> ·
  <a href="https://discord.gg/APV9FYGgeh">Discord</a>
</p>

<p align="center">
  <a href="https://github.com/oxide-terminal/oxide/releases/latest"><img src="https://img.shields.io/github/v/release/oxide-terminal/oxide?color=e2725b" alt="Latest release" /></a>
  <a href="https://github.com/oxide-terminal/oxide/actions/workflows/ci.yml"><img src="https://github.com/oxide-terminal/oxide/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://github.com/oxide-terminal/oxide/blob/main/LICENSE"><img src="https://img.shields.io/github/license/oxide-terminal/oxide" alt="MIT license" /></a>
  <a href="https://discord.gg/APV9FYGgeh"><img src="https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white" alt="Join the Discord" /></a>
</p>

<p align="center">
  <a href="https://github.com/oxide-terminal/oxide"><img src="https://raw.githubusercontent.com/oxide-terminal/oxide/main/assets/screenshots/main.webp" alt="Oxide Terminal: file tree drawer, tabs above a terminal running cargo build, and a git-aware status bar" /></a>
</p>

Oxide is a GPU-rendered terminal built on [GPUI](https://www.gpui.rs) (Zed's UI framework) and
[`alacritty_terminal`](https://crates.io/crates/alacritty_terminal) (Alacritty's PTY and VT parser).
The things you'd normally bolt on — a file tree you drive like vim, tmux-style workspaces and splits,
a powerline prompt, a vim copy mode, scrollback search — are built in, and all of it lives in one
TOML file that reloads when you save.

No account. No AI. No telemetry. The only thing Oxide asks the network is whether GitHub has a newer release.

## Install

**macOS** (12+, Apple Silicon or Intel)

```sh
brew install --cask oxide-terminal/tap/oxide-terminal
```

**Linux** (Wayland or X11, x86_64) — grab the tarball from the
[latest release](https://github.com/oxide-terminal/oxide/releases/latest) and run `./install.sh`,
or build the Arch package from the PKGBUILD in the repo.

Full instructions, including the DMG and Arch routes, are in the
[install docs](https://oxideterminal.com/docs/install/).

## Repositories

| Repo | What it is |
|------|------------|
| [**oxide**](https://github.com/oxide-terminal/oxide) | The terminal itself. Rust, GPUI, MIT licensed. Issues and PRs go here. |
| [**homebrew-tap**](https://github.com/oxide-terminal/homebrew-tap) | The Homebrew cask for macOS. Updated with every release. |

## Get involved

- **Found a bug or want a feature?** Open an issue on [oxide-terminal/oxide](https://github.com/oxide-terminal/oxide/issues).
- **Want to talk?** Join the [Discord](https://discord.gg/APV9FYGgeh) or email [hello@oxideterminal.com](mailto:hello@oxideterminal.com).
- **Want to follow along?** Read the [blog](https://blog.oxideterminal.com) or watch the [changelog](https://oxideterminal.com/changelog/).
