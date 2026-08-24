# Krisenkommunikation

Krisenmodul für PR- und Kommunikationsagenturen: von der ersten Einordnung eines Vorfalls bis zur Lessons-Learned-Auswertung — mit hartem Faktenregime und beschleunigtem Freigabe-Gate für den Ernstfall.

## Arbeitsprinzip

```
        VORSORGE (Friedenszeiten)              ERNSTFALL
┌────────────────────────────┐   ┌─────────────────────────────────┐
│ krisenstab-playbook        │   │ krisen-triage (Stufe 0–3)       │
│  Rollen, Freigaberechte,   │   │   ↓ Faktenliste = einzige       │
│  Szenario-Karten           │   │     erlaubte Quelle             │
│ dark-site (Rohlinge)       │ → │ holding-statement (< 60–90 min) │
│                            │   │ krisen-qa (Sprachregelung)      │
│                            │   │ dark-site scharf schalten       │
└────────────────────────────┘   │   ↓ alles durch                 │
                                 │ krisen-freigabe-gate            │
        NACHSORGE                │   ↓ Logbuch-Pflicht             │
┌────────────────────────────┐   │ Mensch entscheidet & versendet  │
│ krisen-nachbereitung       │ ← └─────────────────────────────────┘
│ 90 Tage krisen-radar       │
└────────────────────────────┘
```

- **Faktensperre**: Kommuniziert wird nur, was in der Triage als bestätigt dokumentiert ist — jede Aussage ist auf ihre Quelle rückführbar.
- **Ein Gate statt zwei**: In aktiven Krisen (Stufe 2–3) ersetzt das `krisen-freigabe-gate` die normalen Gates des Medienarbeit-Moduls — schneller, aber nicht laxer.
- **Logbuch-Disziplin**: Jede Entscheidung und jede Außenäußerung wird protokolliert — Konsistenzanker im Ernstfall, Goldgrube in der Nachbereitung.
- **Mensch entscheidet**: Skills bereiten vor, der Krisenstab gibt frei. Bei Rechtsrisiken (Personenschäden, Ermittlungen, Kapitalmarkt) ist juristische Begleitung Gate-Bedingung.

## Skills

| Skill | Zweck |
|---|---|
| `krisen-triage` | 4-Stufen-Einordnung, Faktenliste, Sofortmaßnahmen, "Nicht tun"-Liste |
| `holding-statement` | Erststatement nach der 4-Elemente-Formel, mit harter Verbotsliste |
| `krisen-qa` | Internes Q&A: härteste Fragen, 3-Ebenen-Antworten, Grenzlinien |
| `krisenstab-playbook` | Vorsorge-Playbook bauen / im Ernstfall aktivieren |
| `dark-site` | Krisen-Webseite vorbereiten und scharf schalten |
| `krisen-freigabe-gate` | Beschleunigtes Pflicht-Gate für alle Krisen-Veröffentlichungen |
| `krisen-nachbereitung` | Abschluss, Lessons Learned, Playbook-Update, 90-Tage-Nachsorge |

## Agent

- **krisen-radar** — beobachtet Berichterstattung und Resonanz zu aktiven Krisen, stuft Lageänderungen ein (🔴 Eskalation / 🟡 Bewegung / 🟢 ruhig) und meldet. Beobachtet nur, kommuniziert nie nach außen.

## Sofort üben

Mit dem fiktiven [Testszenario „Containerbrand Greifenberg"](testakte/README.md) — ein realistischer Samstagmorgen-Ernstfall für den fiktiven Kunden VoltaWerk, inklusive Übungs-Prompts. Funktioniert eigenständig; wer auch das Medienarbeit-Plugin installiert hat, erlebt beide Module im Zusammenspiel (gleiche Kundenakte).

## Grenzen

Das Modul organisiert Kommunikation. Es ersetzt keine Rechtsberatung, keine behördlichen Meldepflichten, keine Sicherheits- oder Versicherungsberatung — und niemals die Entscheidung von Menschen darüber, was nach außen geht.
