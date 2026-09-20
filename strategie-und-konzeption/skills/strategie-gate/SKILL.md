---
name: strategie-gate
description: 'Pflicht-Quality-Gate für Strategie-Deliverables (Positionierung, Messaging-Framework, Kommunikationskonzept): prüft Konsistenzkette, Belege, Austauschbarkeit, Machbarkeit und Akten-Abgleich vor jeder Kundenvorlage. Trigger: "Strategie-Gate", automatisch aus den Strategie-Skills vor Kundenvorlage.'
---

# Strategie-Gate

Das Gate der Strategiephase prüft nicht Rechtschreibung, sondern Tragfähigkeit: Hält das Deliverable dem kritischsten Kunden im Raum stand — und dem Alltag danach? Es läuft vor **jeder** Kundenvorlage eines Strategie-Dokuments (Positionierungs-Optionen, Messaging-Framework, Gesamtkonzept).

## Der Durchgang

### 1. Konsistenzkette (hart)
Stichproben rückwärts durch die Kette: 3 beliebige Maßnahmen → zitieren sie Botschaft und Persona? 3 Botschaften → zahlen sie auf die Positionierung ein und beantworten einen dokumentierten Einwand? Die Positionierung → zitiert sie Erkenntnisse der Analyse? **Ein Kettenglied ohne Rückverweis = nicht bestanden.** Ebenso umgekehrt: Analyse-Erkenntnisse, auf die sich nichts bezieht → in den Anhang.

### 2. Beleg-Prüfung
Jede Markt- und Wettbewerbsbehauptung hat Quelle + Datum oder ist als Hypothese markiert. Jeder Proof Point hält eine kritische Nachfrage aus. Zahlen im Dokument stimmen untereinander überein (Budget in Summary = Budget im Maßnahmenteil; KPI-Zielwerte = Zielkapitel).

### 3. Austauschbarkeits-Test
Kundennamen in Positionierung und Dachbotschaft durch den stärksten Wettbewerber ersetzen. Fällt es nicht auf → zurück in die `positionierung`. (Der häufigste Durchfallgrund — deshalb eigener Schritt.)

### 4. Machbarkeits- und Rahmen-Check
Maßnahmensumme vs. Budgetkorridor und Ressourcen aus `briefing.md`; Zeitplan vs. Freigabewege des Kunden (aus der Akte: wie lange dauern Freigaben wirklich?); versprochene Frequenzen vs. verfügbares Material. Jedes KPI-Ziel hat Messweg und Nullpunkt.

### 5. Akten- und Modul-Abgleich
Widerspricht das Deliverable der Kundenakte (No-Gos, Zahlen-Politik, laufende Sprachregelungen)? Bei Kunden mit Krisenvorgeschichte: Kollidiert eine Botschaft mit Zusagen aus der Krisenkommunikation (Statements, Resolution-Meldungen)? Eine neue Linie, die alte öffentliche Aussagen unglaubwürdig macht, braucht eine bewusste Übergangs-Entscheidung, keinen stillen Wechsel.

### 6. Sprech- und Fremdleser-Test
Dachbotschaft und Kernbotschaften laut lesbar; Management Summary für einen Unbeteiligten verständlich; keine Agentur-Lyrik. Wer präsentiert, kann jede Folie ohne Spickzettel begründen.

## Ergebnis

Kurzprotokoll `gate-<dokument>-<datum>.md` im Projektordner:

```markdown
# Strategie-Gate — <Dokument> (JJJJ-MM-TT)
1 Konsistenzkette: ✓/✗ | 2 Belege: ✓/✗ | 3 Austauschbarkeit: ✓/✗
4 Machbarkeit/Rahmen: ✓/✗ | 5 Akten-Abgleich: ✓/✗ | 6 Sprechbarkeit: ✓/✗
Ergebnis: VORLAGEREIF / NACHARBEIT (konkrete Punkte)
```

Das Gate bereitet die Kundenvorlage vor — die Entscheidung über Strategie und Vorlage treffen Menschen. Bei „NACHARBEIT" wird nachgearbeitet, nicht wegdiskutiert: Was das Gate findet, findet sonst der Kunde.
