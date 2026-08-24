---
name: krisen-freigabe-gate
description: "Beschleunigtes Quality-Gate für Krisenkommunikation: Faktensperre, Verbotsliste, Konsistenz und Freigaberecht in einem Durchgang — ersetzt in Krisen (Stufe 2–3) die normalen Gates des Medienarbeit-Moduls. PFLICHT vor jeder Veröffentlichung aus einem Krisenvorgang. Trigger: 'Krisen-Freigabe', automatisch aus den Krisen-Skills."
---

# Krisen-Freigabe-Gate

In der Krise gibt es keine Zeit für zwei getrennte Gate-Läufe — aber erst recht keine Toleranz für Fehler. Dieses Gate bündelt Fakten- und Freigabeprüfung in einem Durchgang von 10–15 Minuten. Es ersetzt in Krisenvorgängen (Stufe 2–3) die Skills `fakten-gate` und `freigabe-gate` des Medienarbeit-Moduls; bei Stufe 0–1 gelten weiter die normalen Gates.

## Der Durchgang (in dieser Reihenfolge)

### 1. Faktensperre (hart)
Jede Tatsachenaussage im Text muss wörtlich oder sinngleich in `triage.md` unter **"Bestätigte Fakten"** stehen.
- Aussage nicht in der Faktenliste → raus aus dem Text oder (wenn inzwischen bestätigt) erst in die Faktenliste, dann in den Text — nie umgekehrt.
- Zahlen zu Betroffenen/Schäden: nur mit behördlicher Bestätigung, immer mit „nach derzeitigem Stand".

### 2. Verbotsliste
Abgleich gegen die harte Verbotsliste (aus holding-statement): Spekulation, Schuldzuweisung, ungeprüfte Haftungsaussagen, „Kein Kommentar", unangemessene Tonlage. Plus No-Gos aus der Kundenakte.

### 3. Konsistenzprüfung
Widerspricht der Text früheren Statements dieses Vorgangs (Statement-Archiv im Krisenordner) oder dem Q&A? Eine bewusste Korrektur ist erlaubt — aber nur explizit als Korrektur formuliert, nie stillschweigend.

### 4. Rechts-Flag
Bei Personenschäden, möglichen Straftaten, behördlichen Verfahren, Kapitalmarktbezug: Ist die juristische Freigabe dokumentiert (wer, wann)? Fehlt sie → Gate NICHT BESTANDEN, unabhängig vom Zeitdruck. Dieses Gate ersetzt keine Rechtsberatung.

### 5. Empfänger- und Reihenfolge-Check
Stimmt die Stakeholder-Reihenfolge aus dem Playbook (Betroffene/Interne vor Presse, wo möglich)? Richtiger Absender laut Stufe (Pressestelle vs. Geschäftsführung)?

### 6. Freigaberecht
Gibt die laut Krisenstab-Playbook **freigabeberechtigte Person** frei — nicht irgendwer im Verteiler? Name + Zeitpunkt werden dokumentiert.

## Ergebnis

Kurzprotokoll `gate-<dokument>-<zeitstempel>.md` im Krisenordner:

```markdown
# Krisen-Gate — <Dokument> (JJJJ-MM-TT HH:MM)
1 Faktensperre: ✓/✗ | 2 Verbotsliste: ✓/✗ | 3 Konsistenz: ✓/✗
4 Rechts-Flag: ✓/n.a./✗ | 5 Reihenfolge/Absender: ✓/✗ | 6 Freigabe durch: <Name, Zeit>
Ergebnis: FREIGEGEBEN / NICHT FREIGEGEBEN (Gründe)
```

Danach Eintrag ins Logbuch. Veröffentlicht wird ausschließlich durch Menschen nach dokumentierter Freigabe — das Gate bereitet die Entscheidung vor, es trifft sie nicht.

## Grundsatz bei Zeitdruck

Wenn das Gate und die Deadline kollidieren, wird der **Text kürzer, nicht die Prüfung**: Ein Drei-Satz-Statement, das hält, schlägt ein ausführliches, das kippt.
