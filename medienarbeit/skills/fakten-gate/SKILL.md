---
name: fakten-gate
description: "Quality-Gate 1: Prüft jeden nach außen gehenden Text Behauptung für Behauptung gegen Quellen (Kundenakte, Briefing, öffentliche Belege). PFLICHT vor jeder Übergabe an Kunde oder Presse. Trigger: 'Fakten prüfen', 'Fakten-Check', automatisch aus den Produktions-Skills."
---

# Fakten-Gate (Quality-Gate 1 von 2)

Kein Text verlässt die Agentur mit einer ungeprüften Tatsachenbehauptung. Das Fakten-Gate ist kein Stil-Review — es prüft ausschließlich: *Stimmt das, und woher wissen wir es?*

## Verfahren

### Schritt 1: Behauptungen extrahieren
Den Text durchgehen und **jede** Tatsachenbehauptung einzeln listen — auch die unscheinbaren:
- Zahlen, Daten, Termine, Ortsangaben
- Namen, Titel, Funktionsbezeichnungen, Schreibweisen (Firma inkl. Rechtsform!)
- Superlative und Rangaussagen ("erster", "größter", "einziger") — das sind Tatsachenbehauptungen, keine Stilmittel
- Aussagen über Dritte (Partner, Kunden, Wettbewerber, Studien)
- Technische/fachliche Aussagen ("reduziert X um 40 %")
- Implizite Behauptungen ("seit über zehn Jahren…", "als Marktführer…")

### Schritt 2: Jede Behauptung klassifizieren

| Status | Bedeutung | Konsequenz |
|---|---|---|
| ✅ BELEGT | Quelle liegt vor (KNOW-HOW.md, Briefing-Dokument, öffentliche Quelle mit Fundstelle) | Quelle notieren |
| 🟡 PLAUSIBEL, UNBELEGT | Wahrscheinlich richtig, aber keine Quelle greifbar | An Kunde zur Bestätigung — nicht selbst "freibestätigen" |
| 🔴 UNGEKLÄRT / WIDERSPRUCH | Keine Quelle, oder Quellen widersprechen sich | Muss vor Versand geklärt oder gestrichen werden |
| ⚫ RECHTSRISIKO | Aussagen über Dritte, Vergleichs-/Alleinstellungswerbung, Heil-/Wirkversprechen, Kapitalmarktbezug | Markieren + Empfehlung: juristisch prüfen lassen. Das Gate ersetzt keine Rechtsberatung |

Websuche zur Verifikation ist erlaubt und erwünscht (z.B. Rangaussagen, Studienzitate) — Fundstelle mit URL und Abrufdatum dokumentieren. KNOW-HOW.md schlägt Web: Wenn der Kunde eine Zahl anders kommuniziert als das Netz, ist das ein 🔴-Widerspruch, kein stiller Fix.

### Schritt 3: Zahlen-Politik prüfen
Jede Zahl gegen den Abschnitt "Zahlen-Politik" in KNOW-HOW.md: Ist sie überhaupt zur Veröffentlichung freigegeben? Eine korrekte, aber nicht freigegebene Zahl ist ein 🔴.

### Schritt 4: Protokoll schreiben
Ergebnis als `fakten-gate.md` in den Vorgangsordner:

```markdown
# Fakten-Gate — <Dokument> (JJJJ-MM-TT)
| # | Behauptung | Status | Quelle / offene Frage |
|---|---|---|---|
Ergebnis: BESTANDEN / BESTANDEN MIT AUFLAGEN (offene 🟡 an Kunde) / NICHT BESTANDEN
```

## Regeln
- Das Gate ändert den Text nicht eigenmächtig — es meldet. Korrekturen macht der Produktions-Skill, danach läuft das Gate über die geänderten Stellen erneut.
- "Das stand im alten Precedent" ist **kein** Beleg für aktuelle Zahlen (Mitarbeiterzahl, Kundenzahl altern). Precedents belegen Tonalität, nicht Fakten.
- Bestanden heißt: keine 🔴 und keine ⚫ ohne dokumentierte Entscheidung des Nutzers.
