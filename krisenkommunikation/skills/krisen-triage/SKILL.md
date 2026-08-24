---
name: krisen-triage
description: 'Bewertet ein eingehendes Issue (kritische Anfrage, Vorfall, Shitstorm-Anzeichen, Leak) nach dem 4-Stufen-Modell und legt Sofortmaßnahmen, Zuständigkeiten und Zeitfenster fest. IMMER als ERSTER Skill verwenden, wenn etwas krisenverdächtig ist: "kritische Anfrage", "Vorfall", "Shitstorm", "Journalist konfrontiert uns", "es ist etwas passiert".'
---

# Krisen-Triage

Der erste und wichtigste Schritt jeder Krise: nüchtern einordnen, bevor kommuniziert wird. Die Triage verhindert beides — Panik-Overreaction auf Nicht-Krisen und Verharmlosung echter Krisen.

## Schritt 1: Lage erfassen (max. 10 Minuten)

Strukturiert abfragen bzw. aus vorliegenden Informationen extrahieren:

- **Was ist passiert?** (nur Bestätigtes; Gerüchte als Gerüchte kennzeichnen)
- **Woher wissen wir es?** (Quelle: intern, Medienanfrage, Social Media, Behörde)
- **Wer weiß es schon?** (intern / einzelne Journalisten / öffentlich)
- **Gibt es Betroffene?** (Verletzte, Geschädigte, Mitarbeitende, Kunden — Menschen vor Sachschäden)
- **Läuft eine Uhr?** (Antwort-Deadline eines Mediums, laufende Berichterstattung, behördliche Meldepflicht)
- **Eigene Verantwortung?** (klar eigenes Verschulden / unklar / fremdverursacht / Falschbehauptung)

## Schritt 2: Stufe bestimmen

| Stufe | Kriterien | Reaktion | Zeitfenster |
|---|---|---|---|
| **0 — Beobachten** | Einzelne kritische Stimme, kein Aufgriff, kein Schaden | Kein aktives Statement; Monitoring hochfahren (Agent krisen-radar) | Lagecheck alle 24 h |
| **1 — Reaktiv bereit** | Medienanfrage zu kritischem Thema ODER wachsende Social-Resonanz | Sprachregelung reaktiv vorbereiten (krisen-qa); nicht proaktiv kommunizieren | Sprachregelung < 4 h |
| **2 — Aktive Krise** | Berichterstattung läuft/steht bevor; Reputationsschaden konkret; Betroffene vorhanden | Krisenstab aktivieren (krisenstab-playbook), Holding Statement (holding-statement), ggf. Dark-Site scharf schalten | Holding Statement < 60–90 min |
| **3 — Vollkrise** | Personenschäden, behördliche Ermittlungen, existenzbedrohend, überregionale Leitmedien | Alles aus Stufe 2 + Geschäftsführung als Absender + externe Rechts-/Fachberatung zwingend | Erstreaktion < 60 min, dann rollierend |

Bei Unsicherheit zwischen zwei Stufen: die höhere wählen. Herunterstufen ist billig, Heraufstufen unter Zeitdruck teuer.

## Schritt 3: Triage-Protokoll schreiben

`kunden/<slug>/projekte/krise-<datum>-<stichwort>/triage.md`:

```markdown
# Krisen-Triage — <Kunde> / <Stichwort> (JJJJ-MM-TT HH:MM)
Stufe: <0–3> | Nächster Lagecheck: <Zeitpunkt>
## Bestätigte Fakten (mit Quelle)
## Gerüchte / Unbestätigtes
## Betroffene
## Laufende Uhren
## Sofortmaßnahmen (wer, was, bis wann)
## Nicht tun (explizit!)
```

Die Rubrik **"Nicht tun"** ist Pflicht — typische Einträge: nicht spekulieren, keine Schuldzuweisungen, kein "Kein Kommentar", keine Löschaktionen in Social Media (Streisand-Effekt), nicht lügen oder beschönigen.

## Schritt 4: Übergabe

Je nach Stufe die Folge-Skills aufrufen und den Nutzer explizit auf die Stufe und das Zeitfenster hinweisen. Bei Stufe 2–3 zusätzlich immer:
- **Rechts-Flag**: bei möglichen Straftaten, Personenschäden, Behördenkontakt, Kapitalmarktbezug → dringende Empfehlung juristischer Begleitung, bevor irgendetwas rausgeht
- **Faktensperre**: Es wird nur kommuniziert, was in `triage.md` unter "Bestätigte Fakten" steht

## Grundsatz

Die Agentur berät, der Kunde entscheidet. Die Triage liefert eine klare Empfehlung mit Begründung — die Entscheidung über Stufe und Maßnahmen trifft der Krisenstab bzw. der Kunde.
