---
name: pressemitteilung
description: Entwirft eine Pressemitteilung auf Basis der Kundenakte (KNOW-HOW für Fakten und No-Gos, PRECEDENTS für Tonalität, TEMPLATES für Struktur). IMMER verwenden, wenn der Nutzer eine Pressemitteilung, Presseinformation, PM oder Medienmitteilung entwerfen, überarbeiten oder prüfen will.
---

# Pressemitteilung

Erstellt PM-Entwürfe, die ein Redakteur ungekürzt übernehmen könnte. Maßstab ist journalistische Verwertbarkeit, nicht Werbesprache.

## Workflow

### Schritt 0: Kundenakte laden
Lies `kunden/<kunden-slug>/KNOW-HOW.md` und die 2–3 jüngsten PM-Precedents. Existiert keine Akte → zuerst Skill `kundenakte-anlegen`. Existiert eine kundenspezifische PM-Vorlage in `TEMPLATES/`, nutze deren Struktur statt der Standard-Struktur unten.

### Schritt 1: Nachrichtenwert klären
Bevor geschrieben wird, beantworte (ggf. durch Rückfrage):
- **Was ist neu?** (die eine Nachricht — nicht drei)
- **Warum jetzt?** (Anlass, Datum)
- **Warum relevant für wen?** (Zielmedien: Fach, Wirtschaft, Regional, Publikum)
- **Belege?** (Zahlen, Studien, Kunden — nur was laut Zahlen-Politik öffentlich ist)

Wenn kein echter Nachrichtenwert erkennbar ist: das offen sagen und Alternativen vorschlagen (Fachbeitrag, Themen-Pitch statt PM) — keine PM über Nicht-Nachrichten schönschreiben.

### Schritt 2: Entwurf nach Standard-Struktur

```
PRESSEMITTEILUNG                          [oder Kopf aus TEMPLATES]
[Ort], [Datum]

# Headline: max. 80 Zeichen, aktives Verb, die Nachricht — kein Wortspiel-Zwang
## Unterzeile: 1 Satz, präzisiert die Headline mit dem stärksten Fakt

**Lead (1. Absatz):** Wer, was, wann, wo, warum — in 2–3 Sätzen vollständig.
Der Lead muss allein stehen können.

**Absatz 2–3:** Kontext und Belege. Zahlen, Einordnung, Relevanz für die Branche.

**Zitat 1:** [Sprecher:in laut KNOW-HOW] — Haltung/Einordnung, kein Fakten-Recycling.
(Zitat-Qualität: siehe Skill zitat-und-oton)

**Absatz 4:** Details, Verfügbarkeit, nächste Schritte, ggf. Zitat 2 (Partner/Kunde).

**Boilerplate:** wörtlich aus KNOW-HOW.md.

**Pressekontakt:** Agentur-Kontakt laut KNOW-HOW.md.
[Hinweis Bildmaterial/Downloads, falls vorhanden]
```

### Schritt 3: Stil-Regeln anwenden
- Länge: 2.500–3.500 Zeichen inkl. Leerzeichen (ohne Boilerplate). Kürzer ist besser als gestreckt.
- Keine Superlative ohne Beleg ("führend", "einzigartig", "revolutionär" streichen oder belegen).
- Kein Konjunktiv-Marketing ("könnte", "dürfte") im Lead.
- Abkürzungen beim ersten Auftreten ausschreiben.
- Tonalität und typische Formulierungen an den Precedents ausrichten; No-Gos aus KNOW-HOW.md sind absolut.
- Datum, Eigennamen, Titel, Zahlen exakt aus KNOW-HOW.md bzw. Briefing — nichts erfinden. Unbelegtes als `⚠️ ZU KLÄREN: …` markieren.

### Schritt 4: Quality-Gates (Pflicht)
Vor jeder Übergabe an den Kunden:
1. **`fakten-gate`** — jede Tatsachenbehauptung gegen Quelle geprüft
2. **`freigabe-gate`** — Red-Team-Lesung und Freigabe-Checkliste

Kein PM-Entwurf verlässt die Agentur ohne beide Gates. Das Ergebnis der Gates wird unter dem Entwurf dokumentiert.

### Schritt 5: Ablage
Entwurf unter `kunden/<slug>/projekte/<vorgang>/` speichern. Nach finaler Kundenfreigabe und Veröffentlichung: finale Fassung nach `PRECEDENTS/` kopieren (Dateinamenskonvention beachten).

## Varianten
- **Kurz-PM / Meldung** (max. 1.200 Zeichen): Lead + 1 Absatz + Boilerplate — für Personalien, Termine.
- **Englische Fassung**: keine 1:1-Übersetzung; Headline und Zitate neu denken, Datumsformat und Titel-Konventionen des Ziellandes.
