# transport-radar.ch – temporäre Landing Page

Statische Landing Page für **Transport Radar**, ein Studierendenprojekt, das öffentliche
Verkehrsdaten der Schweiz sammelt, verarbeitet und visualisiert.

Erstes Projekt: **Swiss ÖV – Abfahrten & Live-Karte** → https://oev.transport-radar.ch
(aktuell in Entwicklung unter https://transport-radar.cedis-agents.workers.dev/).

## Inhalt

| Datei | Zweck |
| --- | --- |
| `index.html` | Die Seite (HTML + Inline-CSS, kein Build nötig) |
| `assets/favicon.svg` | Logo / Favicon |
| `assets/og-image.png` | Social-Preview (1200×630) für Open Graph / Twitter |
| `robots.txt`, `sitemap.xml`, `site.webmanifest` | SEO / Metadaten |

## Deployment

Reines statisches Hosting, z. B. Cloudflare Pages (Build-Command leer, Output-Verzeichnis `/`).
Alle Links zeigen direkt auf `oev.transport-radar.ch` (nicht auf `öv.`, das nur weiterleitet).
