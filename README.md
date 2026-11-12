# Coloring Brawl Stars Skins — GamesStar website

Static Turkish and English introduction, privacy, terms, and support pages for GamesStar. The public Pages source contains only website files; it does not include the game project, artwork collection, player saves, production reports, or archives.

Public HTTPS address: `https://herdem-herdem.github.io/gamesstar-site/`. The expired custom domain was removed on 12 November 2026; no purchased domain is required. Keep the repository free of a `CNAME` file so subsequent deployments preserve this address.

The legal page text is generated from `Docs/Legal/android-content.json` with `Tools/Legal/build_gamesstar_site.py`. The app privacy, terms, and support wording stays aligned with that canonical source. The privacy pages add a separate website-hosting notice for GitHub Pages.

The site is plain HTML and CSS. It has no third-party scripts, analytics, advertising, cookie, or tracking code. Email links open the visitor's own mail app; they do not send automatically.

To refresh the public pages from the B project root, run:

```sh
.venv/bin/python Tools/Legal/build_gamesstar_site.py
```

GitHub Pages publishes the repository root from the `main` branch.

## Branding — 20 October 2026

The public product name is **Coloring Brawl Stars Skins**, verified against the original 529.aab Android app_name resource and Unity productName. GamesStar remains the publisher. The approved half-line/half-color Spike icon supplies the header/footer logo, hero, favicon, Apple touch icon and sharing image. Blue/cyan light beams and green/purple/coral accents follow the approved icon. The source of truth is `Docs/Brand/brand.json` in the private B project; only public website files and approved logo derivatives belong in this repository.
