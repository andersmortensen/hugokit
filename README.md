<p align="center">
  <img src="https://hugokit.app/images/icon-256.png" width="128" height="128" alt="HugoKit icon">
</p>

<h1 align="center">HugoKit</h1>

<p align="center">
  <strong>Your Hugo sites, one click away.</strong><br>
  A native macOS companion for <a href="https://gohugo.io">Hugo</a>. Manage sites, run servers, and deploy — no terminal needed.
</p>

<p align="center">
  <a href="https://hugokit.app">Website</a> ·
  <a href="https://github.com/andersmortensen/hugokit/releases/latest">Download</a> ·
  <a href="https://github.com/andersmortensen/hugokit/issues">Report a bug</a>
</p>

---

## What is HugoKit?

Hugo is one of the fastest static site generators around — but it lives in the terminal. HugoKit wraps Hugo's CLI in a small, focused macOS app so you can spend less time typing commands and more time writing.

Open a site, hit start, and you're previewing. Hit publish, and you're live.

## Features

- **Multi-site sidebar** — keep all your Hugo sites in one place and switch between them instantly
- **One-click server** — start, stop, and restart `hugo server` without touching the terminal
- **Live log streaming** — structured server output right in the app, with filterable severity levels
- **Deploy from the app** — push to GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any FTP/SFTP host
- **Visual config editor** — edit `hugo.toml` with form fields or raw text, with diff preview before saving
- **Hugo auto-install** — detects your Hugo binary, or downloads and installs it for you
- **Preflight checks** — catches common publish-blocking issues before you deploy, with one-click fixes
- **Menu bar quick access** — start a server or check status without opening the main window
- **Native and lightweight** — built in SwiftUI, designed to feel like a system utility

## Installation

1. Download the latest `HugoKit.dmg` from [Releases](https://github.com/andersmortensen/hugokit/releases/latest)
2. Open the DMG and drag HugoKit to Applications
3. Launch HugoKit — the onboarding wizard will guide you through Hugo detection and adding your first site

### Requirements

- macOS 26.2 or later
- Hugo (HugoKit can install it for you if you don't have it)

## Getting started

On first launch, HugoKit will:

1. Look for an existing Hugo installation and offer to install one if not found
2. Walk you through adding your first site (open an existing one, create a new one, or watch a folder)
3. Show you the main panel where everything lives — server controls, content stats, config, and publish

That's it. No project files to set up, no configuration required.

## FAQ

**Is HugoKit open source?**
The repository is public for issues, releases, and documentation, but the source code is not currently open. Contributions and bug reports are welcome via Issues.

**Does it work with my existing Hugo site?**
Yes. HugoKit reads standard Hugo project structure — `content/`, `themes/`, `hugo.toml` — and doesn't add any HugoKit-specific files to your site.

**Can I use it with Hugo themes from the community?**
Yes. HugoKit doesn't restrict theming. Any theme that works with Hugo works with HugoKit.

**What deploy targets are supported?**
GitHub Pages (via Actions), Netlify, Vercel, Cloudflare Pages, FTP, SFTP, and a local static server for testing builds.

**Where does HugoKit store its data?**
Site references and settings live in macOS UserDefaults. Credentials (GitHub tokens, FTP passwords) live in the macOS Keychain. HugoKit never modifies the contents of your Hugo sites without your explicit action.

## Feedback and bugs

Found a bug or have a feature request? [Open an issue](https://github.com/andersmortensen/hugokit/issues).

For general questions, reach out on the [HugoKit website](https://hugokit.app).

## License

HugoKit is proprietary software. © 2026 Anders Mortensen. All rights reserved.
