# Strategie & Konzeption

Strategiemodul für PR- und Kommunikationsagenturen: vom Briefing über Analyse, Positionierung und Botschaften-Architektur bis zum präsentationsfertigen Kommunikationskonzept — dem Beratungsprodukt, mit dem Agenturen Etats gewinnen. Aufbau entlang des [7-Phasen-Referenzprozesses](referenz/konzeptprozess.md).

> **Status v0.1.0:** gebaut auf Basis etablierter PR-Handwerksstandards; die Praxis-Validierung durch die Pilot-Agentur steht aus und fließt in v0.2 ein.

## Arbeitsprinzip

```
  1 strategie-briefing ──→ 2 umfeld-analyse ──→ 3 zielgruppen-personas
        (Problem)              (Diskurs)             (Menschen)
                                   │                     │
                                   └──────┬──────────────┘
                                          ▼
                              4 positionierung (Entscheidung!)
                                          ▼
                              5 messaging-framework
                                          ▼
                    6+7 kommunikationskonzept (Maßnahmen, KPIs, Dokument)
                                          ▼
                              strategie-gate (Pflicht)
                                          ▼
                     Kunde entscheidet · Freigabe · Präsentation
                                          ▼
              messaging-framework schreibt in die Kundenakte (KNOW-HOW)
              → Medienarbeit, Krise & Content arbeiten auf der neuen Linie
```

- **Roter Faden als Regel**: Problem → Erkenntnis → Positionierung → Botschaft → Maßnahme → KPI. Jedes Element verweist auf das davor; das Gate prüft die Kette.
- **Analyse mit Quellen**: Marktbehauptungen werden belegt oder als Hypothese markiert — ein Konzept, das im Kundentermin bei der ersten Nachfrage kippt, ist keins.
- **Der Mensch entscheidet die Strategie**: KI recherchiert, verdichtet und formuliert Varianten; Positionierungsentscheidung, Zielkonflikte und jede Kundenzusage bleiben beim Strategen.
- **Ergebnisse landen in der Kundenakte**: Nach Kundenfreigabe werden Positionierung, Kernbotschaften, Tonalität und No-Gos in `KNOW-HOW.md` übernommen — das Konzept wird Betriebssystem, nicht Schubladen-PDF.

## Skills

| Skill | Phase | Zweck |
|---|---|---|
| `strategie-briefing` | 1 | Briefing-Aufnahme und Auftragsklärung — das echte Problem hinter dem formulierten Wunsch |
| `umfeld-analyse` | 2 | Markt-, Wettbewerbs-, Medien- und Diskursanalyse mit Quellenpflicht |
| `zielgruppen-personas` | 3 | Zielgruppen segmentieren, Personas mit Informationsverhalten und Einwänden |
| `positionierung` | 4 | Positionierungs-Optionen mit Konsequenzen; der Kunde entscheidet |
| `messaging-framework` | 5 | Botschaften-Architektur; schreibt nach Freigabe in die Kundenakte |
| `kommunikationskonzept` | 6–7 | Maßnahmen, Kanäle, Zeitplan, KPIs — und das Gesamt-Dokument |
| `strategie-gate` | 7 | Pflicht-Gate: Konsistenzkette, Belege, Austauschbarkeits-Test, Machbarkeit |

## Agent

- **themen-radar** — beobachtet wöchentlich die Themen- und Diskurslandschaft der aktiven Kunden, meldet besetzbare Themenfenster und aufziehende Debatten. Beobachtet und schlägt vor — entscheiden und kommunizieren tun Menschen.

## Zusammenspiel mit den anderen Modulen

Dieses Modul **erzeugt**, was die anderen **konsumieren**: Die Kundenakte des Medienarbeit-Moduls (Kernbotschaften, Tonalität, No-Gos) wird hier erarbeitet statt nur abgefragt. Umgekehrt liefern `krisen-nachbereitung` (Lessons Learned) und der `medienresonanz-monitor` Input für Konzept-Reviews.

## Sofort üben

Mit der [Testakte VoltaWerk](testakte/README.md): Der fiktive Kunde braucht nach dem Containerbrand (Übungsszenario des Krisenmoduls) eine Positionierungs-Auffrischung — ein realistischer Konzeptanlass mit vorhandener Vorgeschichte. Funktioniert auch eigenständig ohne die anderen Module.

## Grenzen

Das Modul strukturiert Strategiearbeit und beschleunigt sie. Es ersetzt keine Marktforschung mit Primärdaten, keine Rechts- oder Markenberatung — und niemals das strategische Urteil und die Verantwortung der Beraterin.
