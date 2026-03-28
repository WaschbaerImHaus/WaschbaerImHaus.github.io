# WaschbaerImHaus.github.io

> Startseite aller GitHub-Projekte von WaschbaerImHaus

## Inhalt

Diese Seite listet alle öffentlichen Projekte des GitHub-Accounts [WaschbaerImHaus](https://github.com/WaschbaerImHaus) übersichtlich auf.

Live: **https://waschbaer.github.io/**  (alias https://WaschbaerImHaus.github.io/)

## Projekte

| Projekt | Sprache | Beschreibung |
|---------|---------|--------------|
| [ssh-easy](https://github.com/WaschbaerImHaus/ssh-easy) | Go | SSH-Client mit automatischer Schlüsselgenerierung |
| [text-reader](https://github.com/WaschbaerImHaus/text-reader) | Go | Leser für .md, .txt, .epub, .tex |
| [ai-generated-math-papers](https://github.com/WaschbaerImHaus/ai-generated-math-papers) | Python | KI löst offene Mathematikprobleme |

## Lokale Entwicklung

Da es sich um reines HTML/CSS handelt, reicht ein einfacher HTTP-Server:

```bash
# Python
python3 -m http.server 8080

# Go
go run golang.org/x/tools/cmd/present@latest
```

Dann im Browser: http://localhost:8080

## Struktur

```
.
├── index.html          # Hauptseite
├── style.css           # Stildefinitionen
├── favicon.svg         # Favicon
├── src/
│   └── build.txt       # Build-Zähler
├── docs/               # Zusätzliche Dokumentation
├── CHANGELOG.md        # Versionshistorie
├── BUGS.md             # Fehler-Log
└── FEATURES.md         # Feature-Tracking
```

## Lizenz

MIT – siehe [LICENSE](LICENSE)
