---
name: share-of-voice
description: 'Misst den Anteil des Kunden an der Berichterstattung seines Themenfelds im Vergleich zu den Setup-Wettbewerbern — mit ehrlicher Methodik (gleiche Quellenbasis, dokumentierte Stichprobe, Grenzen ausgewiesen). Verwenden je Reportperiode oder vor Strategie-Reviews. Trigger u.a. "Share of Voice", "wie sichtbar sind wir im Vergleich", "Wettbewerbsvergleich Berichterstattung".'
---

# Share of Voice (SoV)

Share of Voice beantwortet eine einzige Frage: Welchen Anteil der relevanten Berichterstattung im Themenfeld bekommt der Kunde — verglichen mit den im Setup definierten Wettbewerbern? Die Zahl ist nur so glaubwürdig wie ihre Methodik; deshalb ist die Methodik Teil des Ergebnisses.

## Methodik (je Messung dokumentiert)

1. **Gleiche Regeln für alle**: Erhebungszeitraum, Quellenbasis und Suchlogik sind für Kunde und Wettbewerber identisch — dieselben Medienlisten, dieselben Suchbegriffs-Muster (Eigenprofil-Äquivalente je Wettbewerber aus dem Setup). Asymmetrische Erhebung = keine Messung.
2. **Zählregeln festlegen**: Was zählt als Nennung (Artikel mit Nennung im Text vs. nur Headline-Nennungen)? Mehrfachnennungen in einem Artikel = ein Treffer je Akteur. Eigenkanäle (Website, eigene Posts) zählen nicht — SoV misst verdiente Sichtbarkeit.
3. **Gewichtung optional, getrennt ausweisen**: Basis-SoV ungewichtet (Trefferzahl). Zusätzlich optional nach Reichweiten-Klasse gewichtet — beide Werte zeigen, nie mischen.
4. **Qualität neben Menge**: SoV nach Tenor aufschlüsseln, wo erhebbar („viel zitiert" kann auch „viel kritisiert" heißen — ein hoher SoV im Krisenmonat ist kein Erfolg).

## Ablage

`kunden/<slug>/monitoring/sov-<zeitraum>.md`:

```markdown
# Share of Voice — <Kunde> (<Zeitraum>)
Quellenbasis + Suchlogik: … | Zählregeln: … | Lücken: …
| Akteur | Treffer | SoV ungewichtet | SoV gewichtet (optional) | davon kritisch |
|---|---|---|---|---|
## Lesart (2–3 Sätze: was die Verschiebung erklärt)
## Themenfeld-SoV (optional: Anteil an EINEM Kernthema, z. B. der besetzten Lücke)
```

Der **Themenfeld-SoV** ist oft aussagekräftiger als der Gesamt-SoV: Wer die eigene Positionierungs-Lücke besetzen will, misst den Anteil an genau dieser Debatte.

## Regeln

- Erste Messung = Nullpunkt, keine Bewertung; Aussagen erst ab der zweiten Messung (Verschiebung).
- Kleine Stichproben ehrlich behandeln: Unter ~20 Treffern gesamt ist SoV eine Anekdote — dann Trefferliste zeigen statt Prozentbalken.
- Wettbewerber-Berichterstattung wird sachlich erfasst, nie kommentierend („Konkurrent X schwächelt") — die Zahlen sprechen, die Lesart bleibt beim eigenen Kunden.
- Methodenwechsel (neue Quellen, neue Zählregel) bricht die Vergleichbarkeit → im Report als Bruch markieren und Nullpunkt neu setzen.
