# Optimierungsvorschläge

## Geschwindigkeit

- GitHub API via JavaScript laden, um Projektkarten automatisch aktuell zu halten (kein manuelles Update nötig)
- Lazy-Loading für das Avatar-Bild (`loading="lazy"`)

## Architektur

- GitHub Actions Workflow: bei jedem Push werden Karten automatisch aus der API neu generiert und als statisches HTML committed
- Alternativ: einfaches JS-Snippet, das die GitHub API beim Seitenaufruf abfragt

## Design

- Animierte Einblendung der Karten (`@keyframes fadeInUp`)
- Sterne-/Fork-Badge direkt aus der GitHub API

## Sonstiges

- `robots.txt` und `sitemap.xml` für bessere SEO
