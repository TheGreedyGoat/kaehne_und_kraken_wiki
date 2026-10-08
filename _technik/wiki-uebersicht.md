# Wiki-Übersicht & Kategorie-Konventionen

Zentrale Arbeitsdatei des Agenten: Artikel-Index je Kategorie, Konventionen je Kategorie und die chronologische Ereignisliste. Nach jedem Intake aktualisieren (neue Artikel in die Kategorie-Liste, neue Ereignisse in die Timeline einsortieren).

## Struktur des Wikis

- **Kanon-Ordner** (nur Artikel mit kanonischem Inhalt): `orte/`, `fraktionen/`, `npcs/`, `geschichte-timeline/`, `weltregeln/`, `sessions/`
- **`wip/`** – alles Inhaltliche, das noch kein Kanon ist: Agenten-Vorschläge (`status: vorschlag`), offene Ideen/Notizen von Alex (`status: entwurf`), offene Widersprüche (`offene-widersprueche.md`)
- **`_technik/`** – Agenten-Arbeitsdateien und Technik: diese Übersicht, `vorlagen.md`, `obsidian-vault.md`
- `KNOWLEDGE.md` (Topic-Root) – System-Einstiegspunkt, beschreibt Struktur und Artikel-Konventionen

## Orte

- Ein Artikel pro Ort, Dateiname = Artikel-Titel gemäß Namenskonvention (z. B. `Der Malstrom.md`).
- Bei neuen Infos zu einem Ort: bestehenden Artikel aktualisieren, kein Duplikat anlegen.
- Frontmatter gemäß Vorlage in `vorlagen.md`, `kategorie: Ort`.

**Artikel:** [[Der Malstrom]], [[Die Zerrissene See]]

## Fraktionen

- Ein Artikel pro Fraktion, Dateiname = Artikel-Titel gemäß Namenskonvention.
- Typische Abschnitte: Ziel & Ideologie, Struktur & Anführer, Verbündete/Rivalitäten (als Wikilinks), Ressourcen, aktueller Stand.
- Zugehörige NPCs verlinken; im NPC-Artikel die Fraktion eintragen (Betroffenheits-Check!).
- Frontmatter gemäß Vorlage in `vorlagen.md`, `kategorie: Fraktion`.

**Artikel:** [[Diebesgilde]], [[Forschergilde]], [[Handelskompanien]], [[Lantanien]], [[Orden des Weaves]], [[Piratenkönigreich]], [[Piraterie In Der Zerrissenen See]], [[Reich Vescaro]]

## NPCs

- Ein Artikel pro NPC, Dateiname = Artikel-Titel gemäß Namenskonvention (z. B. `Elara Sternenwind.md`).
- Typische Abschnitte: Aussehen, Persönlichkeit, Ziele & Motive, Beziehungen (Wikilinks), Wissenswertes.
- Geheimnisse nur, wenn Alex sie explizit genannt hat.
- Fraktions-/Ortszugehörigkeit eintragen und dort rückverlinken (Betroffenheits-Check!).
- Frontmatter gemäß Vorlage in `vorlagen.md`, `kategorie: NPC`.

**Artikel:** [[Capt'n Griphook]], [[Capt'n Luckyfoot]]

## Geschichte & Timeline

- Ein Ereignis = eine Datei, Dateiname = Artikel-Titel gemäß Namenskonvention, Frontmatter mit `zeit` (z. B. „vor 300 Jahren", „Session 4, Tag 12"), `kategorie: Ereignis`.
- Betroffene Artikel verlinken, neue Ereignisse in die Liste unten einsortieren (ältestes zuerst).

**Ereignisse (chronologisch):**

1. [[Vergessene Zivilisation]] – vor unzähligen Jahrtausenden (Vorgeschichte)
2. [[Rivalität Lantanien–Vescaro]] – laufend (Kolonialzeitalter der Zerrissenen See)

## Weltregeln

- Nur Regeln, die Alex explizit festgelegt hat – keine Standard-D&D-Annahmen als Kanon speichern.
- Eine Datei pro Regelkomplex (z. B. `Magiesystem.md`, `Pantheon.md`).
- Bei neuen Weltregeln prüfen, ob sie bestehende Artikel beeinflussen (z. B. Magiebeschränkungen → Orts- oder NPC-Artikel).
- Frontmatter gemäß Vorlage in `vorlagen.md`, `kategorie: Weltregel`.

**Artikel:** (noch keine)

## Sessions

- Eine Datei pro Session: `session-001-kurztitel.md` (laufende Nummer, dreistellig, Kleinschreibung mit Bindestrichen wie alle Nicht-Wiki-Dateien).
- Nur tatsächlich Geschehenes protokollieren; SL-Geheimnisse und NSC-Pläne nur, wenn Alex sie explizit nennt.
- Am Ende jeder Session-Datei: „Kanon-Änderungen" mit Wikilinks zu den in dieser Session angelegten/geänderten Artikeln.
- Frontmatter gemäß Vorlage in `vorlagen.md`, `kategorie: Session`.

**Protokolle:** (noch keine)

## WIP (`wip/`)

- Hier landen **nur** Vorschläge, die Alex nach dem Ideen-Modus ausdrücklich angenommen und speichern ließ, sowie offene Ideen/Notizen von Alex selbst.
- Jede Datei mit `status: vorschlag` (Agenten-Vorschlag) oder `status: entwurf` (offene Idee) im Frontmatter und passendem Quellenhinweis.
- WIP-Inhalte sind **kein Kanon**: beim Intake und Widerspruchs-Check nicht als Fakt behandeln.
- Wird aus einem Vorschlag Kanon (Alex bestätigt ihn als Fakt), wandert der Inhalt in die passenden Kanon-Artikel; hier bleibt nur der Verweis.
- Dateinamen der artikelähnlichen WIP-Dateien folgen der Titel-Konvention; `offene-widersprueche.md` bleibt Klein-mit-Bindestrich.

**Vorschläge (Agent, von Alex angenommen):** [[Kampagne]], [[Crew-Konzepte]]
**Offene Ideen/Notizen (Alex):** [[Ursprung von Jorys Glück]]
**Widerspruchs-Liste:** `offene-widersprueche.md`
