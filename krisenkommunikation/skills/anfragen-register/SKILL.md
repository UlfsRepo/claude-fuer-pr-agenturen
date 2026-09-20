---
name: anfragen-register
description: 'Führt das Anfragen-Register einer Krise und steuert den Dialog über getrennte Pfade — Medien, Behörden/Aufsicht, Betroffene, Partner. Jede eingehende Anfrage wird erfasst, dem richtigen Pfad zugeordnet, mit Frist versehen und aus der freigegebenen Sprachregelung beantwortet. Verwenden ab Stufe 1–2, sobald Anfragen eingehen. Trigger u.a. "Journalist fragt an", "Behörde meldet sich", "Anfrage beantworten", "Anfragenliste".'
---

# Anfragen-Register & Dialogsteuerung

Im Ernstfall gehen Anfragen über alle Kanäle gleichzeitig ein. Das Register sorgt dafür, dass keine verloren geht, keine Frist reißt — und dass eine Behördenanfrage nie wie eine Medienanfrage behandelt wird. Jede externe Aussage bleibt menschlich verantwortet, ohne Ausnahme.

## Das Register

`kunden/<slug>/projekte/krise-<datum>-<stichwort>/anfragen-register.md`:

```markdown
# Anfragen-Register — <Kunde> / <Stichwort>
| Nr | Eingang | Absender (Name, Organisation) | Pfad | Frage(n) | Frist | Owner | Status | Antwort (Kurzfassung + Zeitpunkt) |
|---|---|---|---|---|---|---|---|---|
```

Status: offen → in Klärung → Antwort freigegeben → beantwortet → nachgefasst. Jede Antwort wird mit Zeitpunkt und Wortlaut-Referenz dokumentiert — spätere Antworten müssen zu früheren passen, das Register ist der Konsistenzanker.

## Die vier Pfade

**Medien** — Antworten ausschließlich entlang des krisen-qa; Deadline erfragen und zusagen, was haltbar ist. Fangfragen erkennen und benennen (Spekulationsaufforderung, Entweder-oder-Falle, "Bestätigen Sie, dass…", hypothetische Szenarien, die Bitte um "nur unter uns") — beantwortet wird die Sachfrage dahinter, auf der Linie der Sprachregelung. Beziehungsarbeit nicht vergessen: Auch eine Absage ("dazu können wir heute noch nichts sagen, Update um …") ist eine Antwort mit Absender.

**Behörden & Aufsicht** — zwingend über Legal, anderes Spielbuch: Fristen sind rechtsverbindlich, jede Aussage kann Teil einer Akte werden. Die Agentur formuliert nicht ohne juristische Zeichnung, wahrt die Fristen im Register und sorgt für Konsistenz mit der Außenkommunikation. Gilt auch für parlamentarische Anfragen und förmliche Auskunftsersuchen.

**Betroffene & Kunden** — Empathie vor Botschaft: konkrete Hilfe, Ansprechpartner, nächste Schritte; keine Pressesprache. Vorsicht bei Schuldanerkenntnis- und Haftungsformulierungen — bei Schadensfällen Formulierungen mit Legal abstimmen. Häufige Fragen aus diesem Pfad als Kandidaten ins Q&A und in die Status-Updates zurückspielen.

**Partner & Multiplikatoren** — Händler, Lieferanten, Verbände, ggf. Konzernstellen: operativ konkreter als die Öffentlichkeit, aber keine vertraulichen Details, die weiterwandern. Reihenfolge und Verteiler aus der stakeholder-matrix.

## Arbeitsregeln

- **Eine Frage, eine Linie**: Vor jeder Antwort prüfen, ob dieselbe Frage schon einmal beantwortet wurde — und wie. Abweichungen sind Entscheidungen des Krisenstabs, keine Versehen.
- **Neue Fragenlinien melden**: Fragen ohne Deckung im Q&A sofort an krisen-qa zur Ergänzung; erst Linie festlegen (und freigeben), dann antworten.
- **Gegennarrativ dokumentieren**: Wiederkehrende (Falsch-)Behauptungen in Anfragen mit dem krisen-radar-Lagebild zusammenführen. Ob aktiv entkräftet wird, entscheidet der Krisenstab — manche Falschbehauptung stirbt schneller ohne Antwort.
- **Schriftlich schlägt mündlich**: Antworten bevorzugt schriftlich oder mit schriftlicher Bestätigung des Gesagten; Telefonate unmittelbar danach im Register protokollieren.
- Wortgleiche Statements an mehrere Redaktionen sind in der Krise legitim und sogar erwünscht (Konsistenz) — Exklusivität gibt es im Ernstfall nicht.
