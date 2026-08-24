---
name: dark-site
description: Bereitet Dark-Site-Inhalte vor — eine unveröffentlichte Krisen-Webseite je Szenario, die im Ernstfall in Minuten live gehen kann. Verwenden in der Krisenvorsorge (nach dem krisenstab-playbook) oder beim Scharfschalten im Ernstfall. Trigger u.a. "Dark Site", "Krisenseite", "Notfallseite vorbereiten".
---

# Dark-Site

Eine Dark-Site ist die vorbereitete, unveröffentlichte Krisenseite: Im Ernstfall ersetzt oder ergänzt sie die normale Website-Kommunikation, damit die Startseite nicht fröhlich Produkte bewirbt, während die Lage ernst ist. Vorbereitung in Friedenszeiten, Scharfschalten in Minuten.

## Modus A: Vorsorge (Inhalte bauen)

Je Szenario aus dem Krisenstab-Playbook einen Seiten-Rohling erstellen, Ablage unter `kunden/<slug>/dark-site/<szenario>/`:

### Seitenstruktur (ein Rohling)
1. **Statement-Bereich**: Holding-Statement-Rohling mit `[PLATZHALTER]` für Ereignis, Datum, Ort — nach der 4-Elemente-Formel des Skills holding-statement. Platzhalter in eckigen Klammern und GROSS, damit im Stress nichts stehenbleibt.
2. **Fakten-Bereich**: „Was wir derzeit wissen" als Liste mit Stand-Zeitstempel — bewusst leer vorbereitet, wird im Ernstfall ausschließlich aus der Triage-Faktenliste gefüllt.
3. **Betroffenen-Bereich**: Hotline/Kontakt für Betroffene und Angehörige `[NUMMER]`, FAQ-Grundstock je Szenario (aus krisen-qa ableitbar — aber nur die veröffentlichbaren Antworten, das interne Q&A bleibt intern!)
4. **Presse-Bereich**: Pressekontakt, Statement-Archiv, Hinweis auf Update-Rhythmus
5. **Update-Log**: chronologisch, neuestes oben, jedes Update mit Zeitstempel

### Zusätzlich vorbereiten
- **Social-Media-Pendants**: je Szenario 1–2 Posts, die auf die Dark-Site verlinken (Kanäle laut Kundenakte)
- **Interne Erstinfo**: kurze Mitarbeiter-Nachricht (Betroffene/Interne vor der Presse — siehe Playbook-Stakeholder-Reihenfolge)
- **Technik-Absprache dokumentieren**: Wer schaltet die Seite live (Name, Vertretung, Weg), wie lange dauert es, wurde es getestet? Die Agentur liefert Inhalte; Hosting/Freischaltung klärt der Kunde mit seiner IT — ungeklärt ist das ein ⚠️-Punkt im Playbook.

### Stil
Nüchtern, barrierearm, ohne Marketing-Elemente: keine Werbebanner, keine Produktnavigation, keine Stock-Betroffenheitsfotos. Kurze Sätze — die Seite wird von gestressten, betroffenen Menschen gelesen.

## Modus B: Ernstfall (Scharfschalten)

1. Passenden Rohling wählen; Platzhalter ausschließlich mit Fakten aus `triage.md` füllen. Bleibt ein `[PLATZHALTER]` ungefüllt, wird der Abschnitt gestrichen, nicht improvisiert.
2. `krisen-freigabe-gate` über die gesamte Seite.
3. Nach Freigabe durch den Krisenstab: Kunde/IT schaltet live; Zeitpunkt ins Logbuch.
4. Update-Disziplin: Jedes neue Statement zuerst auf die Dark-Site, dann auf andere Kanäle verlinken — die Seite ist die eine offizielle Quelle ("single source of truth") der Krise.
5. **Rückbau** nach Krisenende bewusst entscheiden (krisen-nachbereitung): nicht kommentarlos löschen — ein stilles Verschwinden wirkt wie Vertuschung; Abschlussstatement mit Datum stehen lassen oder Archiv-Hinweis setzen.
