# Nabu Beautè

Website für **Nabu Beautè** — Kosmetikstudio in Düsseldorf-Holthausen
(Kölner Landstraße 282, 40589 Düsseldorf).

Vorschau/Deployment über GitHub Pages:
<https://topac57.github.io/Nabu-Beauty/>

## Inhalt

- [`index.html`](index.html) — Startseite (eigenständige Datei, Bilder als
  base64 eingebettet, Schriften via Google Fonts).
- [`assets/images/`](assets/images/) — Quell-Bilder (`.webp`) der Behandlungen
  und Galerie.

## Lokal ansehen

Die Seite ist eine einzelne, eigenständige HTML-Datei. Einfach `index.html`
im Browser öffnen — oder einen kleinen lokalen Server starten:

```bash
python3 -m http.server 8000
# danach: http://localhost:8000
```

## Hinweise

- Der aktuelle Stand stellt die statische Nabu-Beautè-Landingpage aus der
  Git-History wieder her und ist ohne Build-Schritt deployfähig.
- Die in `index.html` angezeigten Bilder sind direkt als base64 eingebettet;
  die Dateien unter `assets/images/` dienen als bearbeitbare Quell-Assets.
- Externe Abhängigkeiten: Google Fonts (Fraunces, Outfit), WhatsApp-Link und
  Google-Maps-Embed.
