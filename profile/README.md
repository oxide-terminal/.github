<p align="center">
  <img src="https://raw.githubusercontent.com/omnipty/omnipty/main/assets/icon_1024.png" width="160" alt="OmniPTY icon — a corroded iron terminal prompt" />
</p>

<h1 align="center">OmniPTY</h1>

<p align="center">
  <strong>The tools you'd normally bolt onto your terminal, built in.</strong><br/>
  A native terminal for macOS and Linux, written entirely in Rust.<br/>
</p>

<p align="center">
  <a href="https://omnipty.com">Website</a> ·
  <a href="https://omnipty.com/docs/">Docs</a> ·
  <a href="https://omnipty.com/changelog/">Changelog</a> ·
  <a href="https://omnipty.com/compare/">Compare</a> ·
  <a href="https://blog.omnipty.com">Blog</a> ·
  <a href="https://discord.gg/APV9FYGgeh">Discord</a>
</p>

<p align="center">
  <a href="https://github.com/omnipty/omnipty/releases/latest"><img src="https://img.shields.io/github/v/release/omnipty/omnipty?color=e2725b" alt="Latest release" /></a>
  <a href="https://github.com/omnipty/omnipty/actions/workflows/ci.yml"><img src="https://github.com/omnipty/omnipty/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://github.com/omnipty/omnipty/blob/main/LICENSE"><img src="https://img.shields.io/github/license/omnipty/omnipty" alt="MIT license" /></a>
  <a href="https://discord.gg/APV9FYGgeh"><img src="https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white" alt="Join the Discord" /></a>
  <a href="https://github.com/sponsors/omnipty"><img src="https://img.shields.io/badge/Sponsor-%E2%9D%A4-e2725b?logo=githubsponsors&logoColor=white" alt="Sponsor on GitHub" /></a>
</p>

<p align="center">
  <a href="https://github.com/omnipty/omnipty"><img src="https://raw.githubusercontent.com/omnipty/omnipty/main/assets/screenshots/main.webp" alt="OmniPTY: file tree drawer, tabs above split panes running cargo test and cargo run, and a git-aware status bar" /></a>
</p>

If your terminal is really a terminal plus a stack of add-ons — tmux for splits and sessions,
a file manager in another pane, a prompt framework, a copy-mode plugin — OmniPTY builds those in.
A file tree you drive like vim sits beside your panes and follows your shell's `cd`. Tabs and
splits group into named workspaces you can pin, so they reopen with the same layout and
directories. Copy mode puts vim keys on the scrollback, and the status bar knows your git
branch and when you're inside `ssh`. It's all configured in one TOML file that reloads when
you save.

Under the hood, it's GPU-rendered on [GPUI](https://www.gpui.rs) (Zed's UI framework), with
[`alacritty_terminal`](https://crates.io/crates/alacritty_terminal) (Alacritty's PTY and VT parser)
doing the emulation, so vim, htop, and tmux itself still just work.

No account. No AI. No telemetry. The only thing OmniPTY asks the network is whether there's a newer release.

## Install

**macOS** (12+, Apple Silicon or Intel)

```sh
brew install --cask omnipty/tap/omnipty
```

**Linux** (Wayland or X11, x86_64) — grab the tarball from the
[latest release](https://github.com/omnipty/omnipty/releases/latest) and run `./install.sh`,
or build the Arch package from the PKGBUILD in the repo.

Full instructions, including the DMG and Arch routes, are in the
[install docs](https://omnipty.com/docs/install/).

## Repositories

| Repo | What it is |
|------|------------|
| [**omnipty**](https://github.com/omnipty/omnipty) | The terminal itself. Rust, GPUI, MIT licensed. Issues and PRs go here. |
| [**homebrew-tap**](https://github.com/omnipty/homebrew-tap) | The Homebrew cask for macOS. Updated with every release. |

## Get involved

- **Found a bug or want a feature?** Open an issue on [omnipty/omnipty](https://github.com/omnipty/omnipty/issues).
- **Want to talk?** Join the [Discord](https://discord.gg/APV9FYGgeh) or email [hello@omnipty.com](mailto:hello@omnipty.com).
- **Want to follow along?** Watch the [changelog](https://omnipty.com/changelog/).
