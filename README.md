# Claude für PR-Agenturen

Installierbare Claude-Code-Plugins für PR- und Kommunikationsagenturen: Skills, Quality-Gates, Monitoring-Agenten und Testakten — gebaut nach dem Muster erprobter Fach-Skill-Sammlungen (Kundenakte als Wissensfundament, Produktions-Skills, verpflichtende Qualitätsprüfung, Mensch entscheidet über Veröffentlichung).

> ⚠️ **Experimentell.** Die Plugins unterstützen Kommunikationsprofis, sie ersetzen keine — und keine Rechtsberatung. Nichts wird ohne menschliche Freigabe versendet oder veröffentlicht.

## Installation

```
/plugin marketplace add <URL-dieses-Repos>
/plugin install medienarbeit@claude-fuer-pr-agenturen
```

Danach mit der fiktiven Testakte VoltaWerk ausprobieren — Schnellstart-Prompts je Modul: [Medienarbeit](medienarbeit/medienarbeit-schnellstart.md) · [Krisenkommunikation](krisenkommunikation/krisenkommunikation-schnellstart.md) · [Strategie & Konzeption](strategie-und-konzeption/strategie-schnellstart.md) · [Monitoring & Reporting](monitoring-und-reporting/monitoring-schnellstart.md)

## Module

| Plugin | Status | Inhalt |
|---|---|---|
| **[medienarbeit](medienarbeit/)** | ✅ v0.1.1 | Kundenakte (3-Ebenen-System), Pressemitteilung, Pitch-Mail, Pressemappe, Verteiler-Strategie, Embargo-Handling, Zitat-Werkstatt, 2 Quality-Gates, Medienresonanz-Monitor, Testakte |
| **[krisenkommunikation](krisenkommunikation/)** | ✅ v0.2.1 | Vollständiger 10-Schritte-Krisenprozess: Triage (4 Stufen), Faktenstand (Ground Truth), Stakeholder-Mapping, Holding Statement, Q&A/Sprachregelung, Krisenstab-Playbook, Dark-Site, Krisen-Freigabe-Gate, Status-Kommunikation, Anfragen-Register, Nachbereitung — plus Krisen-Radar-Agent, Referenzprozess mit SLA-Zielwerten, Prozesslandkarte als Beratungsprodukt, Übungsszenario |
| **[strategie-und-konzeption](strategie-und-konzeption/)** | ✅ v0.1.1 | 7-Phasen-Konzeptprozess: Strategie-Briefing, Umfeld-/Wettbewerbsanalyse, Zielgruppen & Personas, Positionierung mit Härtetests, Messaging-Framework (schreibt in die Kundenakte), Kommunikationskonzept, Strategie-Gate — plus Themen-Radar-Agent und Testszenario. *Praxis-Validierung durch Pilot-Agentur ausstehend.* |
| content-und-social | 🔜 geplant | LinkedIn/Social, Ghostwriting/Namensbeiträge, Newsletter, Redaktionsplan, Corporate-Language-Check |
| **[monitoring-und-reporting](monitoring-und-reporting/)** | ✅ v0.1.1 | Monitoring-Setup mit Nullmessung, Clipping-Erfassung, Medienresonanz-Analyse, Share of Voice, KPI-Report — nach harten Reporting-Prinzipien (kein AVE, Negatives steht im Report). *Praxis-Validierung durch Pilot-Agentur ausstehend.* |
| agency-ops | 🔜 geplant | Briefing-Intake, New-Business-Pitch, Statusberichte, Freigabe-Workflows, Interviewvorbereitung |
| events | 🔜 geplant | Pressekonferenz, Pressegespräch, Messe-Kommunikation |

**Weiterer Ausbau (Roadmap):** Admin- und Business-Module über die PR-Fachlichkeit hinaus — u.a. **CFO/Finance**, **Sales & Business Development**, **Strategy** — nach demselben Bauprinzip.

## Bauprinzip aller Module

1. **Kundenakte als Fundament** — 3 Ebenen: TEMPLATES (Struktur), PRECEDENTS (freigegebene frühere Texte als Tonalitäts-Benchmark), KNOW-HOW (Fakten, Kernbotschaften, No-Gos, Freigabeprozess, Zahlen-Politik)
2. **Produktions-Skills** — erst Akte laden, dann schreiben; nichts erfinden, Unbelegtes markieren
3. **Verpflichtende Quality-Gates** — Fakten-Gate (stimmt das?) und Freigabe-Gate (was macht die Welt damit?) vor jeder Kundenvorlage
4. **Agenten beobachten, Menschen entscheiden** — Monitoring-Agenten melden; Versand und Veröffentlichung brauchen immer ein menschliches Go
5. **Testakte je Modul** — ein fiktiver Kunde zum gefahrlosen Ausprobieren

## Qualitätssicherung (Evals)

Jedes Modul bringt eine Eval-Suite mit (`<modul>/evals/`), die die harten Regeln automatisiert testet — z. B. dass das Fakten-Gate unbelegte Behauptungen blockt, die Kundenakte keine Fantasiewerte erfindet, das Holding Statement Spekulationsdruck widersteht, das Strategie-Gate austauschbare Positionierungen ablehnt und der Report AVE auch auf Kundenwunsch verweigert. Ausführen (benötigt eine Claude-Code-Version mit `plugin eval`):

```
claude plugin eval ./krisenkommunikation --trust-plugin --allow-tools Write Read
```

Einzelfall: `--case <name>`, alle Module nacheinander oder per GitHub Action ([.github/workflows/plugin-evals.yml](.github/workflows/plugin-evals.yml), manuell startbar; benötigt das Repo-Secret `ANTHROPIC_API_KEY`).

## Lizenz & Mitwirken

Noch festzulegen. Feedback und Praxiserfahrungen aus Agenturen sind willkommen (Issues).
