---
name: faktenstand
description: 'Führt den verbindlichen, versionierten Faktenstand (Ground Truth) einer Krise — sammelt Meldungen, markiert Widersprüche, trackt offene Faktenfragen mit Fristen und hält fest, welcher Stand wann von wem freigegeben wurde. Ab Krisen-Stufe 2 die einzige erlaubte Quelle für jede Aussage. Trigger u.a. "Faktenstand", "Ground Truth", "was wissen wir sicher", "Faktenlage aktualisieren".'
---

# Faktenstand (Ground Truth)

Die Triage liefert die erste Faktenliste — der Faktenstand macht daraus die einzige, versionierte Wahrheit des Vorgangs. Keine Sprachregelung, kein Statement, kein Update ohne freigegebenen Faktenstand: Was hier nicht steht, existiert für die Kommunikation nicht.

## Rollen

- **Ground-Truth-Owner**: eine benannte Person (beim Kunden, meist Fachseite oder Technik) stellt Fakten **verbindlich** fest. Die Agentur sammelt, strukturiert und fragt nach — festgestellt wird nur vom Owner. Name und Erreichbarkeit stehen im Krisenstab-Playbook.
- Jede Faktenfrage bekommt einen Owner und eine Frist. Unbeantwortete Fragen nach Fristablauf werden an den Krisenstab eskaliert, nicht stillschweigend verlängert.

## Das Dokument

`kunden/<slug>/projekte/krise-<datum>-<stichwort>/faktenstand.md` — versioniert, neueste Version oben:

```markdown
# Faktenstand — <Kunde> / <Stichwort>
## Version <n> (JJJJ-MM-TT HH:MM) — freigegeben von <Ground-Truth-Owner>
### Bestätigt (je Punkt: Quelle + Zeitpunkt der Feststellung)
### Korrigiert gegenüber Vorversion (alt → neu, Grund)
### Unbestätigt / Gerüchte (mit Herkunft — wird beobachtet, nicht kommuniziert)
### Offene Faktenfragen (Frage | Owner | Frist | Status)
### Widersprüche (Quelle A sagt X, Quelle B sagt Y — ungeklärt)
```

## Arbeitsschritte

1. **Einsammeln**: neue Meldungen aus Technik, Fachseite, Support, Behörden, Monitoring (krisen-radar-Lageberichte) in den Entwurf der nächsten Version übernehmen — mit Quelle und Zeitstempel.
2. **Widersprüche markieren**: Aussagen gegeneinander und gegen frühere Versionen prüfen. Widersprüche werden nie still aufgelöst, sondern als offene Faktenfrage an den Owner gegeben.
3. **Gegen frühere Außenaussagen prüfen**: Weicht der neue Stand von bereits Veröffentlichtem ab? Dann sofortiger Hinweis an den Krisenstab — eine öffentliche Korrektur ist eine Kommunikationsentscheidung (holding-statement / status-kommunikation), keine stille Änderung.
4. **Freigabe einholen**: Version erst nach ausdrücklicher Bestätigung des Ground-Truth-Owners als "freigegeben" markieren. Bis dahin gilt die letzte freigegebene Version.
5. **Nachgelagerte Dokumente prüfen**: Bei jeder neuen Version Holding Statement, Q&A und Statusmeldungen auf inzwischen falsche oder überholte Aussagen abklopfen und Änderungsbedarf melden.

## Regeln

- **Kein Versand ohne Faktenstand**: Das krisen-freigabe-gate prüft jede Veröffentlichung gegen die aktuelle freigegebene Version — Aussagen ohne Deckung fallen durch.
- Fakten werden **festgestellt, nicht abgestimmt**: keine Formulierungen wie "wir könnten sagen, dass…" im Faktenstand. Formulierung ist Sache der Sprachregelung.
- Plausibel ist nicht bestätigt. Auch die Einschätzung des Kunden ("wird schon der Zulieferer gewesen sein") bleibt unter Unbestätigt, bis der Owner sie feststellt.
- Zahlen (Betroffene, Dauer, Schadenhöhe) nur mit Feststellungszeitpunkt — eine veraltete Zahl nach außen ist schlimmer als "wird derzeit ermittelt".

## Grundsatz

Lieber ein dünner Faktenstand, der hält, als ein dicker, der kippt. Jede Korrektur einer eigenen Aussage kostet mehr Vertrauen als ein ehrliches "das wissen wir noch nicht".
