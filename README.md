# KI-Workshop · Make-it Saar 2026
### pioneo × arconsis Saar

Jedes Kind baut sein eigenes Browser-Spiel mit KI-Unterstützung.  
Die Spiele werden automatisch per GitHub Pages veröffentlicht.

---

## Struktur

```
kids/
  _template/       ← Startvorlage für neue Kinder
  <name>/
    index.html     ← Das fertige Spiel
```

## Live-URLs

- Workshop-Seite: https://pioneo.github.io/claude-pioneo-makeit-workshop-2026/
- Spiel eines Kindes: https://pioneo.github.io/claude-pioneo-makeit-workshop-2026/kids/<name>/

## Neues Kind anlegen

1. `kids/_template/` nach `kids/<name>/` kopieren
2. `index.html` bearbeiten
3. Commit & Push → GitHub Pages deployed automatisch

## Deploy

GitHub Actions (`.github/workflows/deploy.yml`) deployed bei jedem Push auf `main`.
