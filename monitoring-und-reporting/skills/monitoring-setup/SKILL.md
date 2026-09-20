---
name: monitoring-setup
description: 'Richtet das Monitoring für einen Kunden ein — Suchprofile (Kunde, Wettbewerber, Themen), Quellenbasis, Bewertungsschema und die Nullmessung für alle KPIs aus dem Konzept. IMMER erster Skill des Moduls je Kunde; ohne Setup kein belastbarer Report. Trigger u.a. "Monitoring einrichten", "Nullmessung", "Suchprofile", "was beobachten wir".'
---

# Monitoring-Setup & Nullmessung

Reporting beginnt nicht beim ersten Report, sondern bei der Frage: Was beobachten wir, wo, und was ist der Ausgangswert? Ohne dokumentiertes Setup sind spätere Verläufe nicht vergleichbar — und ohne Nullmessung ist jede Erfolgszahl Dekoration ([Reporting-Prinzipien](../../referenz/reporting-prinzipien.md), Nr. 2).

## Schritt 1: Mess-Auftrag klären

Aus dem Kommunikationskonzept (Strategie-Modul) oder direkt vom Kunden: Welche Ziele und KPIs sollen gemessen werden, in welchem Rhythmus wird berichtet, an wen? Existiert ein Konzept mit KPI-Tabelle, ist sie die verbindliche Grundlage — keine eigenen Kennzahlen erfinden. Ohne Konzept: Minimal-Set vereinbaren (Clippings + Tenor + 1–2 Wirkungsindikatoren vom Kunden, z. B. Erstanfragen).

## Schritt 2: Suchprofile definieren

`kunden/<slug>/monitoring/setup.md`:

- **Eigenprofil**: Kundenname und Schreibvarianten, Marken/Produkte, Sprecher-Namen, Standorte
- **Wettbewerbsprofil**: die 3–6 Vergleichs-Wettbewerber (aus der Umfeld-Analyse, falls vorhanden) — Basis für Share of Voice
- **Themenprofil**: Themenfelder aus Positionierung/Konzept (z. B. Branchendebatten, Regulierung) — Abgleich mit dem themen-radar-Agenten, falls installiert
- **Risikoprofil**: Begriffe, die Eskalationen früh anzeigen (Kategorie-Vorfälle, kritische Kampagnenbegriffe, laufende Zusagen aus Krisenvorgängen)
- **Quellenbasis**: Welche Quellen werden systematisch erfasst (Fachmedien-Liste, Regionalmedien je Standort, Social-Kanäle, Foren) — und welche bekannten Lücken bestehen (Paywalls, geschlossene Gruppen). Lücken werden dokumentiert, nicht verschwiegen.

## Schritt 3: Bewertungsschema festlegen (einmal, dann bindend)

Damit jede spätere Erfassung gleich bewertet: Reichweiten-Klassen (überregional / regional / fach / nische — mit Beispielmedien je Klasse) · Tenor-Skala (positiv / neutral / kritisch, mit je einem Ankerbeispiel; Grenzfälle konservativ) · Botschaften-Treffer (welche Kernbotschaften aus der Akte gelten als „durchgedrungen" — wörtlich oder sinngemäß zitiert) · **Frame-Zählregel**, falls das Konzept einen Ziel-Frame definiert (wann trägt ein Beitrag den Frame? Typisch: der Deutungsrahmen ist erkennbar, reine PM-Übernahmen ohne Zitat zählen nicht). Schema-Änderungen später = ausgewiesener Methodenwechsel.

## Schritt 4: Nullmessung durchführen

Je KPI aus Schritt 1 den heutigen Wert erheben und mit Datum und Messweg dokumentieren (`nullmessung.md`): Berichterstattungs-Basislinie (letzte 6–12 Monate: Clipping-Zahl, Tenor-Verteilung, Frames), Share-of-Voice-Startwert, Kundendaten (Anfragen, Bewerbungen — beim Kunden anfordern, Owner + Lieferdatum notieren). Nicht erhebbare Nullpunkte als `⚠️ OFFEN` mit Beschaffungsweg — nie schätzen und als Messung ausgeben.

## Schritt 5: Rhythmus und Zuständigkeiten

Erfassungsrhythmus (laufend via Agenten / wöchentlich manuell), Reportrhythmus (aus dem Konzept), Owner je Datenquelle. Verbindung zu den Agenten dokumentieren: `medienresonanz-monitor` (Medienarbeit) liefert Veröffentlichungen, `krisen-radar` Krisenlagen, `themen-radar` Themenfenster — deren Meldungen sind Rohstoff der Erfassung (clipping-erfassung), nicht schon der Report.

## Grundsatz

Das Setup ist ein Vertrag mit der Zukunft: Was hier definiert ist, macht Verläufe über Quartale vergleichbar. Zehn saubere Kennzahlen schlagen dreißig wackelige.
