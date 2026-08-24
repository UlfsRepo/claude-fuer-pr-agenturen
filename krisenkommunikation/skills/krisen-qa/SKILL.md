---
name: krisen-qa
description: Erstellt das Q&A-Dokument (Sprachregelung) für eine Krise — antizipiert die härtesten Journalistenfragen und legt für jede Frage Kernantwort, Vertiefung und Grenzlinie fest. Verwenden ab Krisen-Stufe 1. Trigger u.a. "Q&A", "Sprachregelung", "was antworten wir auf", "Fragenkatalog".
---

# Krisen-Q&A / Sprachregelung

Das Q&A ist das interne Betriebssystem der Krisenkommunikation: Jeder, der nach außen spricht, antwortet auf dieselbe Frage mit derselben Linie. Es wird nie veröffentlicht — es diszipliniert die eigene Seite.

## Aufbau je Frage (3-Ebenen-Antwort)

```markdown
### F: <Frage in der härtesten plausiblen Formulierung>
**Kernantwort** (2–3 Sätze, zitierfähig, hält auch als Einzelzitat)
**Vertiefung** (falls nachgehakt wird: Fakten, Kontext — nur Bestätigtes)
**Grenzlinie** (was wir zu dieser Frage NICHT sagen, und die Brücke zurück:
"Dazu kann ich derzeit nichts sagen, weil <ehrlicher Grund>. Was ich Ihnen
sagen kann: <Brücke zur Kernbotschaft>.")
```

Die Grenzlinie braucht immer einen **ehrlichen Grund** (laufende Untersuchung, Persönlichkeitsrechte, behördliches Verfahren) — „das sagen wir nicht" ohne Grund wirkt wie Vertuschung.

## Fragenkatalog entwickeln

### Schritt 1: Quellen laden
`triage.md`, Holding Statement (falls vorhanden), Kundenakte (No-Gos, Zahlen-Politik).

### Schritt 2: Fragen in 6 Pflichtkategorien antizipieren

1. **Hergang**: Was genau ist passiert? Seit wann wussten Sie davon?
2. **Verantwortung**: Wer ist schuld? Hätte das verhindert werden können? Gab es frühere Warnungen/Vorfälle?
3. **Betroffene**: Wie viele? Wie geht es ihnen? Was tun Sie für sie? Werden Sie entschädigen?
4. **Konsequenzen**: Was ändern Sie? Personelle Konsequenzen? Was kostet das?
5. **Glaubwürdigkeit**: Sie haben doch immer gesagt, dass … — Widersprüche zu früheren Aussagen (gegen PRECEDENTS und alte PMs des Kunden prüfen!)
6. **Zuspitzung/Fallen**: Suggestivfragen, Entweder-oder-Fallen, Hypothesen („Was, wenn sich herausstellt, dass…") — Standardantwort auf Hypothesen: nicht spekulieren, bei Fakten bleiben.

Je Kategorie mindestens 3 Fragen, immer in der **härtesten** Formulierung — ein Q&A, das nur freundliche Fragen übt, ist wertlos.

### Schritt 3: Antworten schreiben
Nach dem 3-Ebenen-Muster. Konsistenz-Pflicht: Keine Antwort darf dem Holding Statement oder einer anderen Antwort widersprechen. Jede Zahl gegen die Faktenliste der Triage.

### Schritt 4: Gate und Pflege
`krisen-freigabe-gate` durchlaufen. Das Q&A ist ein lebendes Dokument: bei jeder Lageänderung aktualisieren, Versionen mit Zeitstempel, Änderungen gegenüber Vorversion oben zusammengefasst.

## Kennzeichnung

Kopfzeile auf jeder Seite: `NUR FÜR DEN INTERNEN GEBRAUCH — NICHT ZUR WEITERGABE` plus Versionsstand. Verteilerkreis des Q&A im Krisenstab-Playbook festhalten — je kleiner, desto dichter.
