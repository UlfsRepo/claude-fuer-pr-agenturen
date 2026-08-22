---
name: verteiler-strategie
description: Baut und pflegt den Medienverteiler eines Kunden (verteiler.md) — Segmente, Empfänger-Recherche-Checkliste, Versandstrategie je Nachricht. IMMER verwenden bei "Verteiler", "an welche Medien", "Presseverteiler", "wen anschreiben", "Versandliste".
---

# Verteiler-Strategie

Der Verteiler ist keine Adressliste, sondern eine Relevanz-Datenbank: Welches Medium interessiert sich wofür, und was haben wir dorthin schon geschickt? Streuverlust ruiniert Beziehungen — 20 passende Kontakte schlagen 500 gekaufte.

## Datenstruktur: `kunden/<slug>/verteiler.md`

```markdown
# Medienverteiler <Kunde>          (Stand: JJJJ-MM-TT)

## Segment: <Name, z.B. "Fachmedien Energie">
Relevanz: <wofür dieses Segment angeschrieben wird>

| Medium | Ressort/Format | Person | Funktion | Kontakt | Notizen (letzte Artikel, Vorlieben, Tabus) | Letzter Kontakt |
|---|---|---|---|---|---|---|
```

Typische Segmente: Fachmedien, Wirtschafts-/Leitmedien, Regionalmedien (Sitz + Standorte), Newsletter/Podcasts/Blogs der Nische, Freie mit Themenschwerpunkt.

## Workflow

### A) Verteiler aufbauen oder erweitern
1. **Themenfelder des Kunden** aus KNOW-HOW.md ableiten (3–6 Begriffe).
2. **Kandidaten recherchieren** (Websuche, Impressum/Autorenzeilen, Mediadaten): Wer hat in den letzten 12 Monaten über diese Themen geschrieben? Je Kandidat: 1–2 konkrete Artikel in die Notizen-Spalte.
3. **Nur belegte Kontakte eintragen.** Kontaktdaten ausschließlich aus öffentlichen Quellen (Redaktionsseite, Impressum, eigenes Profil). Nichts erraten — E-Mail-Schemata ("vorname.nachname@…") nur als `⚠️ unbestätigt` kennzeichnen.
4. **Priorisieren:** je Segment A- (persönlicher Pitch), B- (personalisierte Begleitmail), C-Kontakte (Standardversand).

### B) Versandstrategie je Nachricht
Für eine konkrete PM/Geschichte eine **Versandmatrix** vorschlagen:

| Welle | Wer | Was | Wann |
|---|---|---|---|
| 0 | ggf. 1 Exklusiv-Medium | Exklusiv-Pitch (Skill pitch-mail) | T-x |
| 1 | A-Kontakte betroffener Segmente | individueller Pitch | T |
| 2 | B-/C-Kontakte | PM + kurze Begleitmail | T bzw. T+1 |

Regeln: Exklusiv-Welle blockiert Welle 1 bis Absage/Ablauf. Regionalmedien nur bei Regionalbezug. Wer in den letzten 4 Wochen zweimal kontaktiert wurde und nicht reagiert hat, setzt eine Runde aus.

### C) Pflege
Nach jedem Versand `Letzter Kontakt` aktualisieren; Reaktionen (Veröffentlichung, Absage, "bitte nur noch Thema X") in die Notizen. Abmeldewünsche sind endgültig: Kontakt als `GESPERRT` markieren, nie löschen (sonst wird er neu recherchiert).

## Grenzen
- Keine Anreicherung mit privaten Daten, keine Scraping-Aktionen gegen Nutzungsbedingungen von Plattformen.
- DSGVO-Hinweis für die Agentur in den Verteiler-Kopf aufnehmen: Rechtsgrundlage berechtigtes Interesse (Medienarbeit), Auskunfts-/Löschprozess der Agentur verlinken. Der Skill gibt keine Rechtsberatung.
