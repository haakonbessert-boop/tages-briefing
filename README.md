# Tagesbriefing

Kleine App für den Tagesrahmen: morgens ein Briefing (Training, Top 3, Termine), abends ein kurzes Debrief im Chat mit Claude.

Läuft als Claude-Artifact: https://claude.ai/artifact/RixD9VyTXpEw1C3ToXhUvH

## Aufbau
- `index.html` ist der komplette Quelltext der Seite. Beim Veröffentlichen ergänzt claude.ai das HTML-Grundgerüst (`<!doctype>`, `<head>`, `<body>`).
- Capabilities: `sample` (Abend-Chat und Zusammenfassung über das Claude-Abo), `db` (Debriefs in der Sammlung `tage`, ein Dokument pro Tag `YYYY-MM-DD`, nur für den Besitzer lesbar), `downloads` (Debrief als `.md` für Obsidian).
- Trainingsplan: Mo + Do Push, Di + Fr Pull, sonst Ruhetag.

## Version
v0.1 (28.10.2026)
