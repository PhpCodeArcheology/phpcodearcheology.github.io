# PhpCodeArcheology Website

Landing page for [PhpCodeArcheology](https://github.com/PhpCodeArcheology/PhpCodeArcheology), hosted at [phpcodearcheology.github.io](https://phpcodearcheology.github.io/).

## Stack

- Semantic HTML, no frameworks
- CSS custom properties for theming (light/dark/auto)
- Vanilla JavaScript (theme toggle, hamburger nav, copy buttons)
- Self-hosted fonts (Oswald + Source Sans 3)
- No build step, no dependencies

## Structure

```
index.html          Main landing page
legal.html          Legal notice (Impressum)
privacy.html        Privacy policy (Datenschutzerklärung)
robots.txt          Crawler directives
sitemap.xml         Sitemap
assets/
  css/styles.css    All styles + theme variables
  fonts/            Oswald + Source Sans 3 (WOFF2)
  img/              Favicon, body pattern
```

## Development

Open `index.html` in a browser or start a local server:

```bash
python3 -m http.server 9999
```

No build tools required. Edit `assets/css/styles.css` for styling, HTML files for content.

## License

MIT
