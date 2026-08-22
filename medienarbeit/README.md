# Medienarbeit

Kernmodul für PR- und Kommunikationsagenturen: klassische Pressearbeit von der Kundenakte bis zum Clipping — mit zwei verpflichtenden Quality-Gates vor jeder Veröffentlichung.

## Arbeitsprinzip

```
Kundenakte (3 Ebenen)          Produktion                    Qualität
┌─────────────────────┐   ┌──────────────────────┐   ┌──────────────────┐
│ TEMPLATES  Struktur │ → │ pressemitteilung     │ → │ 1. fakten-gate   │
│ PRECEDENTS Tonalität│   │ pitch-mail           │   │ 2. freigabe-gate │
│ KNOW-HOW   Fakten,  │   │ pressemappe          │   └──────────────────┘
│            No-Gos   │   │ zitat-und-oton       │            ↓
└─────────────────────┘   │ verteiler-strategie  │     Kundenvorlage
    kundenakte-anlegen    │ embargo-und-sperrfr. │   (Versand nur nach
                          └──────────────────────┘    menschlichem Go)
```

- **Kein Text ohne Akte**: Jeder Produktions-Skill lädt zuerst `KNOW-HOW.md` (Fakten, Boilerplate, No-Gos, Zahlen-Politik) und die jüngsten PRECEDENTS (Tonalität).
- **Kein Versand ohne Gates**: `fakten-gate` prüft jede Tatsachenbehauptung gegen Quellen, `freigabe-gate` liest den Text durch vier feindliche Brillen (Redaktion, Wettbewerber, Kritiker, Betroffene) und arbeitet die Freigabe-Checkliste ab.
- **Mensch entscheidet**: Die Gates geben zur Kundenvorlage frei — versendet wird nur nach explizitem Go.

## Skills

| Skill | Zweck |
|---|---|
| `kundenakte-anlegen` | Onboarding-Interview, legt die 3-Ebenen-Akte an |
| `pressemitteilung` | PM-Entwurf mit Nachrichtenwert-Prüfung |
| `pitch-mail` | Individuelle Pitches (exklusiv, thematisch, Nachfass) |
| `pressemappe` | Press Kit mit Lückenliste und Konsistenz-Pass |
| `verteiler-strategie` | Verteiler-Aufbau, Versandmatrix, Pflege |
| `embargo-und-sperrfrist` | Embargo-Entscheidung, Kennzeichnung, Bruchfall-Plan |
| `zitat-und-oton` | Zitat-Werkstatt und reaktive Sprachregelungen |
| `fakten-gate` | Quality-Gate 1: Behauptung-für-Behauptung-Prüfung |
| `freigabe-gate` | Quality-Gate 2: Red-Team-Lesung + Freigabe-Checkliste |

## Agent

- **medienresonanz-monitor** — beobachtet Veröffentlichungen, offene Pitches, Exklusiv-Deadlines und ablaufende Embargos; liefert einen wöchentlichen Statusbericht. Beobachtet nur, versendet nie.

## Sofort ausprobieren

Mit der fiktiven [Testakte VoltaWerk](testakte/README.md) und den [Schnellstart-Prompts](medienarbeit-schnellstart.md) — ohne echten Kunden, ohne Risiko.

## Grenzen

Das Plugin ersetzt weder juristische Prüfung (Wettbewerbs-, Äußerungs-, Kapitalmarktrecht) noch die Veröffentlichungsentscheidung von Menschen. Aussagen mit Rechtsrisiko werden markiert, nicht freigegeben.
