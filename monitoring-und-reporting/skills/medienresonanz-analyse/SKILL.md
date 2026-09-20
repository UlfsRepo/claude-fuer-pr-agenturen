---
name: medienresonanz-analyse
description: 'Wertet die erfassten Clippings eines Zeitraums qualitativ aus — Tenor-Verlauf, Botschaften-Durchdringung, Frames, Medien- und Autoren-Bild, Gegennarrative — und verdichtet zu Erkenntnissen mit Empfehlung. Verwenden vor jedem Report oder auf Zuruf. Trigger u.a. "Resonanzanalyse", "wie kam das an", "Auswertung der Berichterstattung", "Medienanalyse".'
---

# Medienresonanz-Analyse

Die Analyse macht aus der Clipping-Liste ein Lagebild: nicht *wie viel* berichtet wurde, sondern *was hängen bleibt* — und was das für die nächste Arbeitsphase bedeutet. Grundlage: `clippings.md` des Zeitraums plus das Setup-Schema; ohne saubere Erfassung keine Analyse (erst `clipping-erfassung` nachholen und die Lücke ausweisen).

## Auswertungsdimensionen

1. **Mengengerüst** (kurz): Clippings nach Klasse und Anlass — insbesondere der Anteil „ungestützt" (Redaktionen kommen von selbst = stärkstes Sichtbarkeitssignal) und die Ausbeute je eigener PM/Pitch
2. **Tenor-Verlauf**: Verteilung und Entwicklung gegen Vorperiode und Nullmessung; Kippmomente benennen (welches Ereignis hat den Tenor bewegt?)
3. **Botschaften-Durchdringung**: Welche Kernbotschaften werden zitiert, welche nie? Eine Botschaft, die nach zwei Quartalen nirgends auftaucht, ist ein Strategie-Signal (→ Empfehlung), kein Reporting-Detail
4. **Frames**: In welchen Deutungsrahmen erscheint der Kunde (z. B. Sicherheits- vs. Innovations-Frame)? Abgleich mit dem Ziel-Frame aus der Positionierung — Abweichung quantifizieren („Frame-Treffer in x von y Artikeln")
5. **Medien- und Autoren-Bild**: Wer berichtet wiederkehrend, fair, kritisch? Erkenntnisse für Verteiler-Pflege (Medienarbeit-Modul) und Beziehungsarbeit
6. **Gegennarrative & Risiken**: Wiederkehrende kritische Behauptungen mit Herkunft und Entwicklung; bei akuter Dynamik → Übergabe an `krisen-triage`, nicht im Report begraben

## Verdichten

Wie in der Umfeld-Analyse des Strategie-Moduls: 3–6 nummerierte **Erkenntnisse** (R1, R2, …), je ein Satz Befund (mit Zahlen/Belegzitat) + ein Satz Bedeutung + eine konkrete Empfehlung. Empfehlungen sind Pflicht — eine Analyse ohne „und deshalb…" ist Statistik.

## Ablage

`kunden/<slug>/monitoring/resonanz-<zeitraum>.md` mit Kopf: Zeitraum, Quellenbasis, bekannte Lücken, Schema-Version. Einschätzungen (Tenor, Frames) als Einschätzung gekennzeichnet, Zitate belegt.

## Regeln

- Gegen Nullmessung und Vorperiode vergleichen, nie absolut bewerten („12 Clippings" heißt nichts; „12 statt 3, davon erstmals 2 überregional" heißt viel).
- Positiv- und Negativbefunde gleichgewichtig — der Kunde erfährt Kritisches zuerst von der Agentur ([Reporting-Prinzipien](../../referenz/reporting-prinzipien.md), Nr. 3).
- Keine Kausalitäts-Behauptungen ohne Beleg: „zeitgleich mit" schreiben, wenn nur „zeitgleich mit" belegt ist.
- Krisenzeiträume gesondert ausweisen (Sondereffekt), sonst verzerren sie jeden Verlauf.
