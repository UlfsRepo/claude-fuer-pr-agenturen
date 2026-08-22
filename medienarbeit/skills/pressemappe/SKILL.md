---
name: pressemappe
description: Stellt eine vollständige Pressemappe (Press Kit) zusammen — Factsheet, Unternehmensprofil, Sprecher-Biografien, Bildmaterial-Liste, FAQ. IMMER verwenden bei "Pressemappe", "Press Kit", "Pressebereich", "Media Kit", "Factsheet".
---

# Pressemappe

Die Pressemappe beantwortet jede Standardfrage einer Redaktion, ohne dass jemand anrufen muss. Sie wird einmal sauber gebaut und dann versioniert gepflegt — nicht je Anlass neu erfunden.

## Bestandteile (Standard)

1. **Factsheet** (1 Seite): Unternehmen auf einen Blick — Gründung, Sitz, Größe, Geschäftsmodell, Meilensteine als Zeitleiste, 3 Kernzahlen (nur öffentliche laut Zahlen-Politik in KNOW-HOW.md)
2. **Unternehmensprofil** (max. 1 Seite Fließtext): die Geschichte hinter dem Factsheet — Problem, Lösung, Einordnung in den Markt
3. **Sprecher-Biografien**: je Sprecher:in 400–600 Zeichen + Langfassung; nur Personen, die laut KNOW-HOW.md zitierfähig sind
4. **FAQ** (8–12 Fragen): die Fragen, die Journalist:innen wirklich stellen — inklusive der unbequemen (Wettbewerb, Finanzierung, Kritikpunkte). Antworten in freigabefähiger Sprachregelung
5. **Bild- und Materialliste**: verfügbare Fotos, Logos, B-Roll mit Dateiname, Copyright-/Credit-Angabe und Nutzungsbedingungen — nur Material, das tatsächlich existiert; Fehlendes als Beschaffungsliste an den Kunden
6. **Pressekontakt** + Archiv der letzten PMs (Verweis auf PRECEDENTS)

## Workflow

1. **Kundenakte laden** (`KNOW-HOW.md`, PRECEDENTS, ggf. `TEMPLATES/pressemappe*`). Fehlt die Akte → `kundenakte-anlegen`.
2. **Lückenliste zuerst**: Vor dem Schreiben prüfen, welche Bausteine belegt sind. Alles Unbelegte in eine Lückenliste für den Kunden — Fantasie-Meilensteine und geschätzte Zahlen sind verboten.
3. **Bausteine entwerfen** in obiger Reihenfolge; jeder Baustein einzeln als Datei unter `kunden/<slug>/projekte/pressemappe/`, damit Bausteine unabhängig aktualisierbar sind.
4. **Konsistenz-Pass**: Zahlen, Titel und Schreibweisen müssen über alle Bausteine identisch sein — eine Abweichung (z.B. zwei verschiedene Mitarbeiterzahlen) disqualifiziert die ganze Mappe.
5. **Quality-Gates**: `fakten-gate` über alle Bausteine, `freigabe-gate` vor Übergabe.
6. **Versionierung**: Deckblatt-Vermerk `Stand: JJJJ-MM-TT`. Bei Aktualisierung Änderungsliste führen, damit der Kunde gezielt freigeben kann.

## Formate
Standard ist Markdown (Quelle der Wahrheit) + auf Wunsch abgeleitete Formate (PDF, DOCX, Webseiten-Text für den Pressebereich). Die Markdown-Quelle bleibt führend; abgeleitete Formate werden aus ihr erzeugt, nie umgekehrt gepflegt.
