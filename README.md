# Glosso Studio Website

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](LICENSE)
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.145-blue?logo=hugo)](https://gohugo.io)
[![PaperMod](https://img.shields.io/badge/theme-PaperMod-lightgrey)](https://github.com/adityatelange/hugo-PaperMod)

Source code for [glossostudio.com](https://glossostudio.com) — the website for Glosso Studio's independent, privacy-first open-source projects.

## Projects

- **[Glosso Studio](https://glossostudio.com/features/)** — Offline-first pronunciation training app with phoneme-level feedback
- **[TransitOS](https://glossostudio.com/transitos/)** — Real-time public transport trip planner (starts with Metrovalencia)

## Getting Started

Prerequisites: [Hugo](https://gohugo.io/installation/) extended edition v0.145+

```bash
git clone --recurse-submodules https://github.com/IgnacioLD/glosso-studio-website.git
cd glosso-studio-website
hugo server
```

Open http://localhost:1313 in your browser.

### Build for production

```bash
hugo --minify
```

Output goes to `public/`.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This website's content and custom code are licensed under the **GNU AGPL v3**. See [LICENSE](LICENSE).

The [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme is used under its own MIT license.
