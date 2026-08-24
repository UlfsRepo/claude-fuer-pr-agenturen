# Claude für PR-Agenturen

Installierbare Claude-Code-Plugins für PR- und Kommunikationsagenturen: Skills, Quality-Gates, Monitoring-Agenten und Testakten — gebaut nach dem Muster erprobter Fach-Skill-Sammlungen (Kundenakte als Wissensfundament, Produktions-Skills, verpflichtende Qualitätsprüfung, Mensch entscheidet über Veröffentlichung).

> ⚠️ **Experimentell.** Die Plugins unterstützen Kommunikationsprofis, sie ersetzen keine — und keine Rechtsberatung. Nichts wird ohne menschliche Freigabe versendet oder veröffentlicht.

## Installation

```
/plugin marketplace add <URL-dieses-Repos>
/plugin install medienarbeit@claude-fuer-pr-agenturen
```

Danach: [Schnellstart-Prompts](medienarbeit/medienarbeit-schnellstart.md) mit der fiktiven Testakte VoltaWerk ausprobieren.

## Module

| Plugin | Status | Inhalt |
|---|---|---|
| **[medienarbeit](medienarbeit/)** | ✅ v0.1.0 | Kundenakte (3-Ebenen-System), Pressemitteilung, Pitch-Mail, Pressemappe, Verteiler-Strategie, Embargo-Handling, Zitat-Werkstatt, 2 Quality-Gates, Medienresonanz-Monitor, Testakte |
| **[krisenkommunikation](krisenkommunikation/)** | ✅ v0.1.0 | Krisen-Triage (4 Stufen), Holding Statement, Q&A/Sprachregelung, Krisenstab-Playbook, Dark-Site, Krisen-Freigabe-Gate, Nachbereitung, Krisen-Radar-Agent, Übungsszenario |
| strategie-und-konzeption | 🔜 geplant | Kommunikationskonzept, Messaging-Framework, Positionierung, Personas, Umfeldanalyse |
| content-und-social | 🔜 geplant | LinkedIn/Social, Ghostwriting/Namensbeiträge, Newsletter, Redaktionsplan, Corporate-Language-Check |
| monitoring-und-reporting | 🔜 geplant | Clipping-Analyse, Share of Voice, Medienresonanzanalyse, KPI-Reports |
| agency-ops | 🔜 geplant | Briefing-Intake, New-Business-Pitch, Statusberichte, Freigabe-Workflows, Interviewvorbereitung |
| events | 🔜 geplant | Pressekonferenz, Pressegespräch, Messe-Kommunikation |

**Weiterer Ausbau (Roadmap):** Admin- und Business-Module über die PR-Fachlichkeit hinaus — u.a. **CFO/Finance**, **Sales & Business Development**, **Strategy** — nach demselben Bauprinzip.

## Bauprinzip aller Module

1. **Kundenakte als Fundament** — 3 Ebenen: TEMPLATES (Struktur), PRECEDENTS (freigegebene frühere Texte als Tonalitäts-Benchmark), KNOW-HOW (Fakten, Kernbotschaften, No-Gos, Freigabeprozess, Zahlen-Politik)
2. **Produktions-Skills** — erst Akte laden, dann schreiben; nichts erfinden, Unbelegtes markieren
3. **Verpflichtende Quality-Gates** — Fakten-Gate (stimmt das?) und Freigabe-Gate (was macht die Welt damit?) vor jeder Kundenvorlage
4. **Agenten beobachten, Menschen entscheiden** — Monitoring-Agenten melden; Versand und Veröffentlichung brauchen immer ein menschliches Go
5. **Testakte je Modul** — ein fiktiver Kunde zum gefahrlosen Ausprobieren

## Lizenz & Mitwirken

Noch festzulegen. Feedback und Praxiserfahrungen aus Agenturen sind willkommen (Issues).
