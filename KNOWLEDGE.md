---
name: dnd-welt
description: "Kanon-Wiki von Alex' D&D-Kampagnenwelt: Orte, Fraktionen, NPCs, Timeline, Weltregeln. Verwaltet vom Skill dnd-wiki; nur explizit von Alex gegebene Infos sind Kanon."
display_name: D&D-Welt Wiki
icon: 🐉
---

# D&D-Welt Wiki

Persönlicher Kanon-Store von Alex' D&D-Welt, verwaltet vom dnd-wiki-Agenten. Ziel: eine widerspruchsfreie, strukturierte Wiki-Quelle, die jederzeit nach Obsidian exportiert werden kann.

## Kernprinzipien

- **Kanon** ist nur, was Alex explizit als Fakt für die Welt gegeben hat.
- Eigene Ideen des Agenten werden nur als **Vorschlag** geäußert und nie ohne Alex' Zustimmung gespeichert.
- Jede neue Information wird gegen den bestehenden Kanon geprüft; Widersprüche landen in [offene-widersprueche.md](offene-widersprueche.md) und werden Alex gemeldet.

## Struktur

- [Orte](orte/KNOWLEDGE.md) – Städte, Regionen, Länder, Gebäude
- [Fraktionen](fraktionen/KNOWLEDGE.md) – Gilden, Orden, Reiche, Gruppierungen
- [NPCs](npcs/KNOWLEDGE.md) – benannte Einzelfiguren
- [Geschichte & Timeline](geschichte-timeline/KNOWLEDGE.md) – Ereignisse in chronologischer Ordnung
- [Weltregeln](weltregeln/KNOWLEDGE.md) – Magie, Götter, Kosmologie, Hausregeln
- [Sessions](sessions/KNOWLEDGE.md) – Protokolle gespielter Sitzungen (Kanon-Quelle)
- [Ideen & Vorschläge](ideen/KNOWLEDGE.md) – nur mit Alex' Zustimmung gespeicherte Agenten-Ideen

## Zentrale Dateien

- [Offene Widersprüche](offene-widersprueche.md) – Plotholes, Logiklücken, ungelöste Konflikte
- [Vorlagen](vorlagen.md) – Artikel-Vorlagen mit Frontmatter

## Artikel-Konventionen

- Deutschsprachige Artikel, Obsidian-kompatibles Markdown, Wikilinks: `[[Artikelname]]`
- YAML-Frontmatter gemäß Vorlage, mit `status: kanon` oder `status: entwurf`
- Titel: jedes Wort groß geschrieben, Leerzeichen bleiben Leerzeichen (z. B. `npcs/Elara Sternenwind.md`)
- Nicht-Wiki-Dateien (z. B. `offene-widersprueche.md`, `vorlagen.md`, Session-Protokolle) und die `KNOWLEDGE.md`-Dateien: Kleinschreibung mit Bindestrichen
- Wikilinks nur auf existierende oder gerade erstellte Artikel, Schreibweise exakt wie der Zielartikel-Titel – keine Links auf fehlende Seiten
- Titel bestehender Artikel werden vom Agenten nie selbst geändert; Titel-Vorschläge als Notiz an den Anfang der Datei
