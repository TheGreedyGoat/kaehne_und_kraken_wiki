# Vorlagen

Obsidian-kompatible Artikel-Vorlagen für das D&D-Welt-Wiki. Frontmatter immer vollständig ausfüllen.

Dateiname = Artikel-Titel: jedes Wort groß geschrieben, Leerzeichen bleiben Leerzeichen (z. B. `Reich Vescaro.md`). Nicht-Wiki-Dateien (diese Vorlagen hier, `offene-widersprueche.md`, Session-Protokolle) verwenden Kleinschreibung mit Bindestrichen.

## Allgemeiner Artikel

```markdown
---
titel: <Anzeigename>
kategorie: Ort | Fraktion | NPC | Ereignis | Weltregel | Session
tags: []
status: kanon
zuletzt-aktualisiert: YYYY-MM-DD
---

# <Name>

> Kurzfassung in 1–2 Sätzen.

## Details

<Strukturierte Fakten.>

## Verbindungen

- Verwandte Artikel als [[Wikilinks]]

## Quellen

- Wann/wie Alex diese Info gegeben hat (z. B. „Alex, Chat 2026-10-07", „Session 3").
```

## NPC (zusätzlich zu „Details")

- Aussehen
- Persönlichkeit
- Ziele & Motive
- Beziehungen (zu [[NPCs]], [[Fraktionen]], [[Orten]])
- Geheimnisse – nur wenn von Alex explizit genannt

## Fraktion (zusätzlich zu „Details")

- Ziel & Ideologie
- Struktur & Anführer
- Verbündete / Rivalitäten (als Wikilinks)
- Ressourcen & Einfluss
- Aktueller Stand in der Kampagne

## Ort (zusätzlich zu „Details")

- Lage & Beschreibung
- Bevölkerung & Machthaber
- Wichtiges Geschehen (mit Timeline-Links)

## Ereignis (Timeline)

```markdown
---
titel: <Ereignisname>
kategorie: Ereignis
zeit: <z. B. „vor 300 Jahren" oder „Session 4, Tag 12">
tags: []
status: kanon
zuletzt-aktualisiert: YYYY-MM-DD
---
```

- Beteiligte: [[NPCs]], [[Fraktionen]], [[Orte]]
- Was geschah, welche Folgen hatte es
