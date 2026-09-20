# Krisenkommunikation

Krisenmodul für PR- und Kommunikationsagenturen: von der ersten Einordnung eines Vorfalls bis zur Lessons-Learned-Auswertung — mit hartem Faktenregime, beschleunigtem Freigabe-Gate und einem vollständigen [10-Schritte-Referenzprozess](referenz/krisenprozess.md) inklusive SLA-Zielwerten und KI-Einsatz-Landkarte.

## Arbeitsprinzip

```
        VORSORGE (Friedenszeiten)                ERNSTFALL (rechnet in Minuten)
┌──────────────────────────────┐   ┌──────────────────────────────────────────┐
│ krisen-prozesslandkarte      │   │ krisen-triage (Stufe 0–3)                │
│  Prozess, KI-Einsatz, SLAs   │   │ faktenstand ← einzige erlaubte Quelle    │
│ krisenstab-playbook          │   │ krisenstab-playbook aktivieren           │
│  Rollen, Freigaberechte,     │ → │ stakeholder-mapping — wer spricht, wer   │
│  Szenario-Karten             │   │  erfährt es wann (parallel)              │
│ dark-site (Rohlinge)         │   │ holding-statement (< 60–90 min)          │
│                              │   │ krisen-qa (Sprachregelung)               │
│                              │   │   ↓ alles durch krisen-freigabe-gate     │
│                              │   │ status-kommunikation — Statusquelle      │
│                              │   │  zuerst, getaktete Updates, dark-site    │
│                              │   │ anfragen-register — Medien / Behörden /  │
│                              │   │  Betroffene / Partner getrennt           │
│                              │   │   ↓ Logbuch-Pflicht                      │
│        NACHSORGE             │   │ Mensch entscheidet & versendet           │
┌──────────────────────────────┐   └──────────────────────────────────────────┘
│ krisen-nachbereitung         │ ←
│ 90 Tage krisen-radar         │
└──────────────────────────────┘
```

- **Faktensperre**: Kommuniziert wird nur, was im freigegebenen `faktenstand` steht — jede Aussage ist auf ihre Quelle rückführbar, der Ground-Truth-Owner stellt Fakten verbindlich fest.
- **Single Source of Truth**: Eine Statusquelle publiziert zuerst, alle Kanäle verweisen darauf. Jede Lücke in der Taktung füllt das Gegennarrativ.
- **Ein Gate statt zwei**: In aktiven Krisen (Stufe 2–3) ersetzt das `krisen-freigabe-gate` die normalen Gates des Medienarbeit-Moduls — schneller, aber nicht laxer.
- **Getrennte Pfade**: Eine Behördenanfrage ist keine Medienanfrage — das `anfragen-register` hält Medien, Aufsicht, Betroffene und Partner auseinander; der Behördenpfad läuft zwingend über Legal.
- **Logbuch-Disziplin**: Jede Entscheidung und jede Außenäußerung wird protokolliert — Konsistenzanker im Ernstfall, Goldgrube in der Nachbereitung.
- **Mensch entscheidet**: KI erkennt, entwirft und taktet — Faktenfeststellung, Einstufung, Absenderklärung, jede Freigabe und jede externe Aussage bleiben menschlich. Bei Rechtsrisiken (Personenschäden, Ermittlungen, Kapitalmarkt) ist juristische Begleitung Gate-Bedingung.

## Skills

| Skill | Prozessschritt | Zweck |
|---|---|---|
| `krisen-prozesslandkarte` | Vorsorge | Beratungsprodukt: kompletter Krisenprozess mit Automatisierungs-/KI-Landkarte, SLAs und Roadmap für einen Kunden |
| `krisenstab-playbook` | 4 | Vorsorge-Playbook bauen / im Ernstfall aktivieren: Rollen, Meldeketten, Krisenraum |
| `krisen-triage` | 3 | 4-Stufen-Einordnung, Sofortmaßnahmen, "Nicht tun"-Liste |
| `faktenstand` | 2 | Verbindlicher, versionierter Ground Truth — offene Faktenfragen mit Fristen, Widerspruchs-Check |
| `stakeholder-mapping` | 5 | Wer spricht, wer erfährt es wann — Absenderklärung, Matrix, Informationsreihenfolge |
| `holding-statement` | 6 | Erststatement nach der 4-Elemente-Formel, mit harter Verbotsliste |
| `krisen-qa` | 6 | Internes Q&A: härteste Fragen, 3-Ebenen-Antworten, Grenzlinien |
| `krisen-freigabe-gate` | 7 | Beschleunigtes Pflicht-Gate für alle Krisen-Veröffentlichungen |
| `status-kommunikation` | 8 | Statusquelle, nummerierte Updates, Taktung, Kanalvarianten, Resolution-Meldung |
| `dark-site` | 8 | Krisen-Webseite vorbereiten und scharf schalten |
| `anfragen-register` | 9 | Anfragen-Register mit Fristen; getrennte Pfade für Medien, Behörden, Betroffene, Partner |
| `krisen-nachbereitung` | 10 | Abschluss, Lessons Learned, Playbook-Update, 90-Tage-Nachsorge |

Schritt 1 (Signalerfassung & Monitoring) übernimmt der Agent:

## Agent

- **krisen-radar** — beobachtet Berichterstattung und Resonanz zu aktiven Krisen, stuft Lageänderungen ein (🔴 Eskalation / 🟡 Bewegung / 🟢 ruhig) und meldet. Beobachtet nur, kommuniziert nie nach außen.

## Referenzprozess

[referenz/krisenprozess.md](referenz/krisenprozess.md) beschreibt den generischen 10-Schritte-Prozess: SLA-Zielwerte (erste Reaktion ≤ 60 min, kritischer Pfad 45 min), das Automatisierungs-Zielbild (20–30 % automatisiert, 30–40 % KI-gestützt, 35–50 % bewusst menschlich), Prinzipien sowie typische Risiken mit ihren Kontrollen. Die Skills setzen den Prozess um; die `krisen-prozesslandkarte` schneidet ihn als Beratungsprodukt auf einen konkreten Kunden zu.

## Sofort üben

Mit dem fiktiven [Testszenario „Containerbrand Greifenberg"](testakte/README.md) — ein realistischer Samstagmorgen-Ernstfall für den fiktiven Kunden VoltaWerk, inklusive Übungs-Prompts. Funktioniert eigenständig; wer auch das Medienarbeit-Plugin installiert hat, erlebt beide Module im Zusammenspiel (gleiche Kundenakte).

## Grenzen

Das Modul organisiert Kommunikation. Es ersetzt keine Rechtsberatung, keine behördlichen Meldepflichten, keine Sicherheits- oder Versicherungsberatung — und niemals die Entscheidung von Menschen darüber, was nach außen geht.
