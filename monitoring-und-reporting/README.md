# Monitoring & Reporting

Mess- und Reportingmodul für PR- und Kommunikationsagenturen: vom Monitoring-Setup mit Nullmessung über einheitliche Clipping-Erfassung, Resonanz-Analyse und Share of Voice bis zum periodischen KPI-Report — nach harten [Reporting-Prinzipien](referenz/reporting-prinzipien.md) (Wirkungstreppe, Nullpunkt-Pflicht, kein AVE, Negatives steht im Report).

> **Status v0.1.0:** gebaut auf Basis etablierter Mess-Standards; Praxis-Validierung durch die Pilot-Agentur steht aus.

## Arbeitsprinzip

```
EINMAL JE KUNDE                LAUFEND                      JE PERIODE
┌────────────────────┐   ┌──────────────────────┐   ┌──────────────────────────┐
│ monitoring-setup   │   │ Agenten melden:      │   │ medienresonanz-analyse   │
│  Suchprofile,      │ → │  medienresonanz-     │ → │  (R1–Rn + Empfehlungen)  │
│  Bewertungsschema, │   │  monitor, krisen-    │   │ share-of-voice           │
│  NULLMESSUNG       │   │  radar, themen-radar │   │        ↓                 │
└────────────────────┘   │ clipping-erfassung   │   │ kpi-report               │
                         │  (einheitl. Schema)  │   │  + Ehrlichkeits-Check    │
                         └──────────────────────┘   │  + Freigabe-Gate         │
                                                    │  → Kunde                 │
                                                    └──────────────────────────┘
```

- **Nullpunkt-Pflicht**: Keine Kennzahl ohne Ausgangswert und Zielwert — die Nullmessung gehört zum Setup, nicht zum ersten Report.
- **Ein Schema, bindend**: Reichweiten-Klassen, Tenor-Anker und Botschaften-Treffer werden einmal definiert; Änderungen sind ausgewiesene Methodenwechsel.
- **Ehrlichkeit als Produktmerkmal**: keine Reichweiten-Summen-Poesie, kein Werbeäquivalenzwert (auch nicht auf Kundenwunsch), Stichproben und Lücken transparent, Kritisches steht im Report.
- **Der Report trägt die Wiedervorlagen**: Konzept-Reviews, Hypothesen-Validierungen und zugesagte Folgeberichte (auch aus Krisen-Resolutionen) laufen als Pflicht-Rubrik mit — nichts versandet.

## Skills

| Skill | Zweck |
|---|---|
| `monitoring-setup` | Suchprofile, Quellenbasis, Bewertungsschema, Nullmessung — der Vertrag mit der Zukunft |
| `clipping-erfassung` | Veröffentlichungen einheitlich erfassen und bewerten (Klasse, Tenor mit Beleg, Botschaften-Treffer, Anlass) |
| `medienresonanz-analyse` | Qualitative Auswertung je Zeitraum: Tenor-Verlauf, Durchdringung, Frames, Gegennarrative — mit Empfehlungen |
| `share-of-voice` | Wettbewerbsvergleich mit dokumentierter, symmetrischer Methodik |
| `kpi-report` | Der periodische Kundenreport gegen Nullpunkte und Konzept-Ziele, inkl. Ehrlichkeits-Check |

## Zusammenspiel mit den anderen Modulen

Das Modul **schließt den Loop**: Es misst gegen die KPI-Tabelle des Kommunikationskonzepts (Strategie-Modul) und speist Erkenntnisse zurück (Botschaften-Durchdringung → Messaging-Review, Autoren-Bild → Verteiler-Pflege der Medienarbeit, Gegennarrative → Krisen-Triage). Die Monitoring-Agenten der anderen Module (`medienresonanz-monitor`, `krisen-radar`, `themen-radar`) liefern den Rohstoff — das Modul funktioniert aber auch eigenständig mit manueller Erfassung.

## Sofort üben

Mit der [Testakte VoltaWerk](testakte/README.md): erster Quartalsreport nach dem Konzeptstart, inklusive fiktiver Clipping-Liste zum Auswerten — schließt an die Testszenarien der Module Krisenkommunikation und Strategie an, funktioniert aber eigenständig.

## Grenzen

Das Modul strukturiert Messung und Reporting; es ersetzt keine Marktforschung, keine Werbewirkungsforschung und keine Analytics-Plattformen — und die Interpretation verantwortet die Beraterin, nicht die Tabelle.
