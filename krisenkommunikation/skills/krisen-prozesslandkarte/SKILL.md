---
name: krisen-prozesslandkarte
description: 'Erstellt als Beratungsprodukt die Prozesslandkarte Krisenkommunikation für einen Kunden — den 10-Schritte-Prozess mit Automatisierungspotenzial, KI-Einsatz, menschlicher Verantwortung, SLA-Zielwerten und Umsetzungs-Roadmap, zugeschnitten auf Organisation und Krisentypen des Kunden. Verwenden in Friedenszeiten als Vorsorge-/Beratungsprojekt. Trigger u.a. "Prozesslandkarte", "Krisenprozess aufsetzen", "Automatisierungspotenzial Krisenkommunikation", "KI-Einsatz im Krisenprozess".'
---

# Krisen-Prozesslandkarte (Beratungsprodukt)

Ein Vorsorge-Deliverable der Agentur: die komplette Prozesslandkarte Krisenkommunikation für einen Kunden auf einer Seite — wer verantwortet, was automatisiert wird, wo KI hilft, was zwingend menschlich bleibt, und in welchen Schritten der Kunde dorthin kommt. Grundlage ist der [Referenzprozess](../../referenz/krisenprozess.md); die Beratungsleistung ist der Zuschnitt auf den Kunden.

## Schritt 1: Kundenkontext erheben

Fehlendes strukturiert erfragen (der Nutzer spricht für den Kunden oder holt Antworten ein):

- **Organisation**: Wer ist Process Owner? Gibt es Konzern-/Marken-/Partnerstrukturen mit Abstimmungspflichten? Rufbereitschaft und Vertretung vorhanden?
- **Krisentypen im Scope**: die realistischen 5–8 Szenarioklassen dieses Kunden (z. B. Betriebsunfall, IT-/Datenvorfall, Produktproblem, Regulatorik, Personalie, Social-Media-Eskalation, Lieferketten-/Partnerkrise) — nicht generisch übernehmen, sondern aus Geschäftsmodell und Vorgeschichte ableiten
- **Inputs/Signale**: Wo würde eine Krise zuerst sichtbar (Monitoring, Support-Tickets, Partner, Behörden, Medien)?
- **Zielgruppen & Kanäle**: Wer muss erreicht werden, worüber, in welchen Sprachen? Gibt es eine Statusquelle oder muss sie geschaffen werden?
- **Ist-Reifegrad** je Prozessschritt ehrlich einstufen: Manuell → Teilautomatisiert → Integriert → Intelligent
- **Werkzeuglage**: Monitoring-Tools, Freigabe-Workflows, KI-Zugang, Übersetzung

## Schritt 2: Landkarte erstellen

`kunden/<slug>/projekte/prozesslandkarte-krisenkommunikation/prozesslandkarte.md` — Struktur:

1. **Kopf**: Process Owner · Prozessziel (ein Absatz: aus einem Ereignis keine Vertrauenskrise werden lassen) · Krisentypen im Scope · Input → Output · Zielgruppen · Zuliefernde Funktionen · KPIs
2. **Gesamt-Zielbild**: Anteil automatisiert / KI-gestützt / menschlich (Referenz: 20–30 % / 30–40 % / 35–50 % — menschlicher Anteil bewusst höher als in anderen Comms-Prozessen) · Zeit bis zur ersten Reaktion (Ziel ≤ 60 min)
3. **Die 10 Prozessschritte**, je Schritt vier Zeilen:
   - *Ziel-Automatisierungsgrad* (aus dem Referenzprozess, an den Ist-Reifegrad des Kunden angepasst)
   - *Was kann automatisiert werden* (konkret mit den Werkzeugen des Kunden)
   - *KI-Einsatz* (sinnvolle Anwendungen — erkennen, bündeln, entwerfen, prüfen, takten)
   - *Menschliche Verantwortung* (nicht verhandelbar: Faktenfeststellung, Einstufung, Absenderklärung, jede Freigabe, Rechtsauslegung, Tonalität, jede externe Aussage)
4. **SLA-Tabelle** für die höchste Stufe, mit kritischem Pfad und ausgewiesenem Puffer — Zielwerte müssen rechnerisch haltbar sein, nicht nur ambitioniert
5. **Umsetzungs-Roadmap** in drei Horizonten:
   - **Quick Wins (0–3 Monate)**: Rollen mit Namen und Vertretung besetzen · Ground-Truth-Owner mit SLA benennen · Alarmierungskaskade und Krisenraum automatisieren · Statusquelle und Taktung einüben · Szenario-Playbooks bündeln · Holding Statements je Krisentyp vorab juristisch freigeben
   - **Integrierter Workflow (3–9 Monate)**: Freigabe-Workflow mit SLA-Uhr und Audit-Trail · Monitoring-Schwellenwerte an Eskalationsstufen koppeln · automatische Kanalverteilung · KI-Entwurf für Erstmeldung und Updates · Übersetzungs-Workflow mit Fallback-Regel
   - **Agentischer Prozess (9–18 Monate)**: KI-Agenten für Signalerkennung und Lagebild · Konsistenzprüfung über alle Kanäle und Sprachen · Gegennarrativ-Erkennung mit Handlungsvorschlag · Learning Loop: jeder Vorfall aktualisiert die Playbooks
6. **Risiken & Kontrollen** und **Prinzipien** aus dem Referenzprozess, um kundenspezifische ergänzt (z. B. Konzern-Zuständigkeit, Aufsichtspfad, Mehrsprachigkeit)
7. **Ein Prozess, mehrere Fälle**: 2–4 realistische (anonymisierte oder fiktive) Fälle des Kunden zeigen, wo derselbe Prozess jeweils besonders gefordert ist — das verankert, dass der Prozess gelernt wird, nicht das Szenario

Auf Wunsch zusätzlich als HTML-One-Pager für die Präsentation beim Kunden.

## Schritt 3: Übergabe in die Umsetzung

Die Landkarte ist Startpunkt, nicht Endprodukt. Direkt anschließen: `krisenstab-playbook` (Rollen, Meldeketten), `dark-site` (Statusquelle vorbereiten), `holding-statement` im Vorsorge-Modus (Rohlinge je Krisentyp), Übung mit einem Testszenario. Wiedervorlage: Landkarte und Reifegrad jährlich sowie nach jeder `krisen-nachbereitung` prüfen.

## Grundsatz

Keine Automatisierungs-Prozentzahl ohne Begründung, kein KI-Einsatz ohne benannte menschliche Kontrolle daneben. Der Satz, der jede Landkarte abschließt: **Automatisierung beschleunigt und entlastet — die menschliche Verantwortung bleibt entscheidend für Fakten, Freigaben, Tonalität und jede externe Aussage.**
