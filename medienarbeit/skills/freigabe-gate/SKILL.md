---
name: freigabe-gate
description: "Quality-Gate 2: Red-Team-Lesung und Freigabe-Checkliste vor Übergabe an Kunde oder Versand an Presse — liest den Text durch die Augen von Journalist, Wettbewerber, Kritiker und Betroffenen. PFLICHT als letztes Gate nach dem fakten-gate. Trigger: 'Freigabe', 'letzter Check', 'Red Team', automatisch aus den Produktions-Skills."
---

# Freigabe-Gate (Quality-Gate 2 von 2)

Läuft **nach** dem Fakten-Gate. Das Fakten-Gate fragt "Stimmt das?" — das Freigabe-Gate fragt "Was macht die Welt damit?" Es simuliert die unfreundlichste plausible Lesart, bevor es die Öffentlichkeit tut.

## Teil A: Red-Team-Lesung (4 Perspektiven)

Den Text nacheinander durch vier Brillen lesen und je Perspektive die stärkste Attacke notieren:

1. **Gelangweilte Redakteurin** (100 Mails/Tag): Wo steige ich aus? Was ist Phrase statt Nachricht? Würde ich das drucken — und was würde ich zuerst streichen?
2. **Wettbewerber mit Anwalt**: Welche Aussage kann man angreifen (Alleinstellung, Vergleich, Herabsetzung)? Welche Zahl würde man öffentlich anzweifeln?
3. **Kritischer Beobachter** (NGO, Gewerkschaft, Netz-Öffentlichkeit): Was lässt sich als Greenwashing, Übertreibung, Widerspruch zu früherem Verhalten oder Taktlosigkeit lesen? Welcher Satz wird aus dem Kontext gerissen zitiert?
4. **Betroffene/Genannte** (Mitarbeitende, Kunden, Partner, im Text erwähnte Personen): Fühlt sich jemand vorgeführt, vereinnahmt oder übergangen? Sind alle Genannten einverstanden, genannt zu werden?

Je Perspektive: Fundstelle + Attacke + Empfehlung (umformulieren / streichen / bewusst so lassen mit Begründung).

## Teil B: Freigabe-Checkliste

| # | Prüfung | ✓ |
|---|---|---|
| 1 | Fakten-Gate BESTANDEN (Protokoll liegt im Vorgangsordner) | |
| 2 | No-Gos aus KNOW-HOW.md: kein Treffer | |
| 3 | Kernbotschaften: mindestens eine transportiert, keine verfälscht | |
| 4 | Boilerplate wörtlich und aktuell aus KNOW-HOW.md | |
| 5 | Alle Zitate von den zitierten Personen freigegeben (kein `[ENTWURF]`-Marker mehr) | |
| 6 | Embargo-Prüfung (Skill embargo-und-sperrfrist): Sperrfrist nötig? Korrekt gekennzeichnet? | |
| 7 | Empfänger korrekt (richtiges Segment, kein Exklusiv-Konflikt laut pitch-log) | |
| 8 | Rechtschreibung, Schreibweisen, Datumsangaben konsistent | |
| 9 | Ansprechpartner + Kontaktdaten aktuell | |
| 10 | Freigabeprozess des Kunden eingehalten (richtige Personen, richtige Reihenfolge laut KNOW-HOW.md) | |

## Ergebnis

`freigabe-gate.md` im Vorgangsordner:
- **FREIGEGEBEN ZUR KUNDENVORLAGE** — alle Punkte ✓, Red-Team-Funde behandelt
- **ZURÜCK AN PRODUKTION** — mit priorisierter Mängelliste

## Regeln
- Das Gate gibt zur **Kundenvorlage** frei, nie zum Versand: Die finale Veröffentlichungsentscheidung trifft immer ein Mensch (Kunde bzw. Nutzer). Versand ohne dokumentiertes Kunden-Go ist ausgeschlossen.
- Red-Team-Funde werden nie stillschweigend wegoptimiert, wenn sie inhaltliche Entscheidungen sind: Zuspitzung vs. Sicherheit entscheidet der Nutzer.
- Bei Texten mit Krisenpotenzial (Perspektive 3 findet schwere Attacken): explizite Empfehlung, das Krisen-Playbook zu nutzen statt normaler Freigabe.
- Ist ein Persona-/ICP-Check-Skill installiert (z.B. für Social-Content), läuft er zusätzlich — er ersetzt dieses Gate nicht.
