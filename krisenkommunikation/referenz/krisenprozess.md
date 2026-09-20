# Referenzprozess Krisenkommunikation (10 Schritte)

Der generische End-to-End-Prozess, auf den alle Skills dieses Moduls einzahlen. Er gilt für alle Krisentypen — was sich je Fall unterscheidet, ist nur Schwerpunkt und Geschwindigkeit. Deshalb wird der **Prozess** gelernt und geübt, nicht das einzelne Szenario.

## Die 10 Schritte und ihre Skills

| # | Schritt | Skill / Agent | Ziel-Automatisierung |
|---|---|---|---|
| 1 | Signalerfassung & Monitoring | Agent `krisen-radar` | sehr hoch — KI erkennt Anomalien, Themencluster, Gegennarrative |
| 2 | Verifikation & Ground Truth | `faktenstand` | mittel — KI bündelt und markiert Widersprüche, **Mensch stellt Fakten fest** |
| 3 | Klassifikation & Eskalation | `krisen-triage` | mittel–hoch — KI schlägt Stufe vor, **Mensch stuft verbindlich ein** |
| 4 | Krisenteam-Aktivierung & Rollen | `krisenstab-playbook` | hoch — Alarmierung, Krisenraum, Protokoll automatisierbar |
| 5 | Zuständigkeit & Stakeholder-Mapping | `stakeholder-mapping` | mittel — KI schlägt vor, **Mensch klärt verbindlich, wer spricht** |
| 6 | Botschaften & Sprachregelung | `holding-statement`, `krisen-qa` | hoch — KI entwirft aus Playbook + Faktenstand, **Mensch verantwortet jede Aussage** |
| 7 | Freigabe (fachlich, rechtlich, compliant) | `krisen-freigabe-gate` | niedrig–mittel — SLA-Uhr und Audit-Trail automatisch, **Freigabe bleibt menschlich** |
| 8 | Publikation & Kanalsteuerung | `status-kommunikation`, `dark-site` | sehr hoch — Statusquelle zuerst, Varianten und Versand automatisierbar |
| 9 | Dialogsteuerung: Medien, Partner, Behörden | `anfragen-register` | niedrig — jede externe Aussage bleibt menschlich, ohne Ausnahme |
| 10 | Resolution, Deeskalation & Lernen | `krisen-nachbereitung` | hoch — Chronologie und Learnings-Entwurf aus dem Logbuch |

Schritte 4 und 5 laufen parallel; die Freigaben in Schritt 7 ebenfalls.

## SLA-Zielwerte (aktive Krise, Stufe 3)

| Schritt | Zielwert |
|---|---|
| Signalerfassung | laufend · Alarm < 5 min |
| Verifikation & Ground Truth | 10 min bis erster Faktenstand |
| Klassifikation & Eskalation | 5 min |
| Krisenteam-Aktivierung | 10 min bis handlungsfähig |
| Zuständigkeit & Stakeholder-Mapping | 10 min (parallel zu Schritt 4) |
| Botschaften & Sprachregelung | 10 min bis Entwurf |
| Freigabe (Fach / Recht / Krisenleitung) | je 15 min (parallel) · Eskalation nach Ablauf |
| Publikation | 5 min nach Freigabe |
| Dialog & Taktung | Updates alle 30–60 min bis Resolution |
| Nachbereitung | < 10 Arbeitstage |
| **Erste Reaktion gesamt** | **≤ 60 min nach Feststellung** |

Der kritische Pfad bis zur Publikation beträgt 45 Minuten — der 60-Minuten-Zielwert enthält 15 Minuten Puffer und ist damit rechnerisch haltbar, nicht nur ambitioniert. Bei Stufe 2 gelten die weicheren Fenster aus der `krisen-triage`. **Krisenkommunikation rechnet in Minuten, nicht in Arbeitstagen** — das ist der Unterschied zu allen anderen Comms-Prozessen.

## Automatisierungs-Zielbild

- **20–30 %** vollautomatisiert (Alarmierung, Verteiler, Protokoll, Versand, Audit-Trail)
- **30–40 %** KI-gestützt — KI erkennt, entwirft und taktet, der Mensch entscheidet
- **35–50 %** menschliche Entscheidung & Verantwortung — bewusst höher als in anderen Comms-Prozessen

Nicht delegierbar an KI oder Automatik: die verbindliche Feststellung der Fakten, die Einstufung, die Klärung des Absenders, jede Freigabe, die Rechtsauslegung (zeichnet ausschließlich Legal), Tonalität und Empathie, die Entscheidung, was bewusst **nicht** gesagt wird — und jede externe Aussage.

## Prinzipien

1. **Faktenbasiert** — keine Spekulation über Ursache, Dauer oder Verantwortung
2. **Proaktiv** — lieber einmal zu viel als einmal zu spät
3. **Single Source of Truth** — eine Statusquelle, alle Kanäle verweisen darauf
4. **Lösungsorientiert** — nie nur das Problem, immer der nächste Schritt
5. **Konsistent** — gleiche Botschaft über alle Kanäle, Marken und Sprachen
6. **Ohne Schuldzuweisung** — weder intern noch extern
7. **Dokumentiert** — jede Entscheidung mit Zeitstempel und Owner (Logbuch)
8. **Lernend** — jeder Vorfall verbessert Playbook und Prozess

## Typische Risiken und ihre Kontrollen

| Risiko | Kontrolle |
|---|---|
| Meldung ohne Faktenstand | Kein Versand ohne Freigabe des Ground-Truth-Owners (`faktenstand`) |
| KI-Entwurf ungeprüft | Vier-Augen-Prinzip; jede Aussage bleibt menschlich verantwortet |
| Ein Kanal prescht vor | Statusquelle publiziert zuerst; alle anderen Kanäle danach (`status-kommunikation`) |
| Recht rutscht in die Sprachregelung | Legal zeichnet die Rechtsauslegung, Comms formuliert |
| Behördenanfrage wie Medienanfrage behandelt | Getrennte Pfade im `anfragen-register`; Behördenpfad zwingend über Legal |
| Stille | Jede Lücke in der Taktung füllt das Gegennarrativ — Zwischenmeldung auch ohne Neuigkeit |
| Zuständigkeit ungeklärt | Wer spricht (Kunde, Dachmarke, Konzern) wird in Schritt 5 verbindlich festgelegt |
| Sprachversionen laufen auseinander | Kernbotschaft zentral, nur Lokaldetails lokal |
| Playbooks veralten | Post-Incident-Review ist Pflichtschritt, nicht Kür (`krisen-nachbereitung`) |
