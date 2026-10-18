# GamesStar website

Static Turkish and English introduction, privacy, terms, and support pages for GamesStar. The public Pages source contains only website files; it does not include the game project, artwork collection, player saves, production reports, or archives.

Custom domain: `gamesstar.herdem.net.tr` (DNS-only CNAME to `herdem-herdem.github.io`). GitHub Pages is provisioning its HTTPS certificate. HTTP currently returns the site; the old GitHub Pages URL redirects to the custom domain, so do not treat either URL as secure until certificate provisioning completes and HTTPS enforcement is available.

The legal page text is generated from `Docs/Legal/content.json` with `Tools/Legal/build_gamesstar_site.py`. The app privacy, terms, and support wording stays aligned with that canonical source. The privacy pages add a separate website-hosting notice for GitHub Pages.

The site is plain HTML and CSS. It has no third-party scripts, analytics, advertising, cookie, or tracking code. Email links open the visitor's own mail app; they do not send automatically.

To refresh the public pages from the B project root, run:

```sh
.venv/bin/python Tools/Legal/build_gamesstar_site.py
```

GitHub Pages publishes the repository root from the `main` branch.
