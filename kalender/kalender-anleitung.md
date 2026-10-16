# Calendarium-Kalender „Zerrissene See – Zeitrechnung"

Import-Datei für das Obsidian-Plugin **Calendarium** (Idee I-003). Import in Obsidian über die Calendarium-Einstellungen → **Import Calendar** → Datei `kalender/zerissene-see-kalender.json` auswählen.

## Was der Kalender abbildet (Stand I-003)

- **Tag:** 24 Stunden (Weltrotation)
- **Woche:** 6 Tage – Thromachadh, Astar, Glacadh, Ceannas, Theanas, Obrach (halbierter gegenseitiger Mondumlauf; der gegenseitige Umlauf selbst ergibt sich aus Wochennummer + Wochentag und wird nicht separat dargestellt)
- **Monat:** 30 Tage = 5 Wochen (vollständiger Umlauf beider Monde um die Welt); Monate übergangsweise durchnummeriert (1.–12. Monat), da Monatsnamen noch offen sind
- **Jahr:** 360 Tage = 12 Monate (Sonnenjahr)
- **Wochen laufen monats- und jahresübergreifend weiter** (Option `overflow`), der Aggressor-Wechsel (gerade/ungerade Woche) folgt daraus
- **Monde:** Heller Mond und Dunkler Mond (Arbeitsnamen) mit je 30-Tage-Phase und identischem Start – beide teilen sich dieselbe Umlaufbahn um die Welt, zeigen also theoretisch immer die gleiche Phase. Der Kalender zeigt klassische Mondphasen, keine gegenseitige Verdeckung (die ergibt sich aus Wochennummer + Wochentag).

## Was der Kalender NICHT abbildet

- **Planares Jahr (Großjahr, 6 Sonnenjahre):** Die benannten Jahre (Nach den Schatten, Vor den Feen, Feensommer, Nach den Feen, Vor den Schatten, Grauwinter) sind in Calendarium nicht als wiederkehrender Zyklus darstellbar. Umrechnung siehe unten.

## Jahres-Umrechnung (Epochen-Anker, vorläufig)

- **Epochenbeginn:** Sonnenjahr 1 = „Nach den Schatten" im **1. planaren Zyklus**.
- **Formel:** Sonnenjahr = (Zyklus − 1) × 6 + Position im Zyklus (1–6).
- **Kampagnen-Gegenwart (vorläufig, Alex 2026-10-16):** „Das 1000. Nach den Schatten" = Sonnenjahr **5995** – der Kalender startet dort (1. Monat, Tag 1; genaues aktuelles Datum in Obsidian anpassen).
- Jahresnamen: 1 = Nach den Schatten, 2 = Vor den Feen, 3 = Feensommer, 4 = Nach den Feen, 5 = Vor den Schatten, 6 = Grauwinter.

## Offene Punkte

- Zyklus-Anker endgültig klären (aktuell vorläufig: Gegenwart im 1000. Zyklus).
- Monatsnamen festlegen und im Kalender + Wiki nachziehen.
- Mondnamen (aktuell „heller Mond"/„dunkler Mond" als Arbeitsnamen).
- Ggf. Feensommer/Grauwinter als wiederkehrende Events im Kalender markieren.
