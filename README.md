# transport-radar.ch – temporäre Landing Page

Statische Landing Page für **Transport Radar**, ein Studierendenprojekt, das öffentliche
Verkehrsdaten der Schweiz sammelt, verarbeitet und visualisiert.

Erstes Projekt: **swiss-oev** → https://öv.transport-radar.ch
(aktuell in Entwicklung unter https://transport-radar.cedis-agents.workers.dev/).

## Inhalt

| Datei | Zweck |
| --- | --- |
| `index.html` | Die Seite (HTML + Inline-CSS, kein Build nötig) |
| `assets/favicon.svg` | Logo / Favicon |
| `assets/og-image.png` | Social-Preview (1200×630) für Open Graph / Twitter |
| `robots.txt`, `sitemap.xml`, `site.webmanifest` | SEO / Metadaten |

## Vorschau-Screenshot

Die Browser-Vorschau zeigt standardmässig eine schematische SVG-Grafik. Sobald
`assets/preview.png` (idealerweise 1280×800, Screenshot von swiss-oev) existiert,
wird automatisch der echte Screenshot angezeigt.

## Deployment

Reines statisches Hosting, z. B. Cloudflare Pages (Build-Command leer, Output-Verzeichnis `/`).
Hinweis: `öv.transport-radar.ch` entspricht in DNS dem Punycode `xn--v-tga.transport-radar.ch`.
