---
name: clipping-erfassung
description: 'Erfasst Veröffentlichungen (Clippings) strukturiert nach dem Bewertungsschema des Monitoring-Setups — Quelle, Reichweiten-Klasse, Tenor mit Belegzitat, Botschaften-Treffer, Anlass. Laufend verwenden, sobald Berichterstattung erscheint; Grundlage jeder Analyse. Trigger u.a. "Clipping erfassen", "es gab einen Artikel", "Berichterstattung dokumentieren", "Clipping-Liste".'
---

# Clipping-Erfassung

Ein Clipping ist erst dann Daten, wenn es einheitlich bewertet ist. Diese Erfassung macht aus „es gab einen Artikel" einen Datensatz, der sich über Monate auswerten lässt — nach dem bindenden Bewertungsschema aus dem `monitoring-setup`.

## Erfassung

`kunden/<slug>/monitoring/clippings.md` — eine Tabelle, neueste oben:

```markdown
| Datum | Medium | Titel + Link | Klasse | Tenor | Botschaften-Treffer | Frame-Treffer | Anlass | Notiz |
|---|---|---|---|---|---|---|---|---|
```

- **Klasse**: Reichweiten-Klasse laut Setup-Schema (überregional / regional / fach / nische) — keine Auflagen-/Reichweitenzahlen addieren
- **Tenor**: positiv / neutral / kritisch laut Ankerbeispielen; **jede Nicht-neutral-Einstufung mit Belegzitat** in der Notiz; Grenzfälle konservativ (Richtung kritisch)
- **Botschaften-Treffer**: welche Kernbotschaft wörtlich oder sinngemäß zitiert wurde (Nummer aus der Kundenakte) — „gar keine" ist ein valider und wichtiger Wert
- **Frame-Treffer**: ✓/✗ nach der Frame-Zählregel des Setups (nur wenn ein Ziel-Frame definiert ist; sonst Spalte weglassen)
- **Anlass**: eigene PM / Pitch / reaktive Anfrage / ungestützt (Redaktion von selbst) / Krisenvorgang — die Spalte, die später zeigt, welche Arbeit wirkt

## Quellen der Erfassung

Meldungen der Agenten (`medienresonanz-monitor`, `krisen-radar`, `themen-radar`), eigene Recherche-Runden laut Setup-Rhythmus, Hinweise von Kunde und Redaktionen. Jedes Clipping nur einmal (Duplikate über Link prüfen); Agentur-fremde Quellen (Kunde schickt Screenshot) mit Herkunftsvermerk.

## Regeln

- **Vollständigkeit vor Schönheit**: Kritische Artikel werden genauso erfasst wie positive — eine Lücke in der Liste fällt spätestens auf, wenn der Kunde den Artikel selbst findet.
- Bewertung ist Einschätzung: Bei strittigem Tenor beide Lesarten notieren und im nächsten Report offenlegen, nicht stillschweigend entscheiden.
- Social-Erwähnungen mit Reichweite (Threads, auffällige Posts) werden als eigener Typ erfasst (Klasse „social"), nicht mit Presse-Clippings vermischt.
- Krisen-Clippings zusätzlich im Krisenvorgang referenzieren (Logbuch/Lagebericht) — eine Erfassung, zwei Verweise, keine Doppelbewertung.
- Erfasst wird laufend, nicht erst vor dem Report — rückwirkendes Sammeln produziert Lücken, die niemand mehr schließen kann.
