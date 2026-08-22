---
name: pitch-mail
description: Entwirft individuelle Pitch-Mails an Journalist:innen (Themenangebot, Exklusiv-Angebot, PM-Nachfass) auf Basis von Kundenakte und Verteiler-Segment. IMMER verwenden bei "Pitch", "Journalisten anschreiben", "Redaktion anbieten", "Exklusiv anbieten", "Nachfassen".
---

# Pitch-Mail

Eine Pitch-Mail verkauft eine Geschichte an genau eine Redaktion — sie ist das Gegenteil eines Massenversands. Maßstab: Würde diese Journalistin in 15 Sekunden erkennen, warum das Thema zu *ihrem* Ressort und *ihren* letzten Artikeln passt?

## Workflow

### Schritt 0: Kontext laden
- `kunden/<slug>/KNOW-HOW.md` (Kernbotschaften, No-Gos, Sprecher:innen)
- `kunden/<slug>/verteiler.md` — das Segment und, wenn vorhanden, die Empfänger-Notizen (Ressort, letzte relevante Artikel, bevorzugter Kontaktweg)
- Der Aufhänger: PM, Studie, Ereignis oder Themenidee

### Schritt 1: Pitch-Typ bestimmen
| Typ | Wann | Kern |
|---|---|---|
| **Exklusiv-Pitch** | Starke Nachricht, ein Leitmedium zuerst | Exklusivität explizit + Deadline für Antwort |
| **Themen-Pitch** | Kein tagesaktueller Anlass | Geschichte/These anbieten, Kunde als Beleg-Quelle |
| **Experten-Pitch** | Aktuelle Debatte, Kunde kann einordnen | Sprecher:in + 2–3 pointierte Thesen + Verfügbarkeit |
| **PM-Begleitmail** | PM-Versand an Segment | 3–4 Sätze: warum relevant für dieses Ressort |
| **Nachfass** | 3–5 Werktage nach Versand, ohne Reaktion | Neuer Mehrwert (Zahl, Bild, Interview-Slot) — nie "wollte nur nachfragen" |

### Schritt 2: Entwurf

**Betreff** (max. 60 Zeichen): die Nachricht oder These — kein "Pressemitteilung:", kein Clickbait. Bei Exklusiv: "Exklusiv angeboten: …"

**Struktur (max. 150 Wörter Fließtext):**
1. **Personalisierter Einstieg (1 Satz):** Bezug auf konkrete Arbeit der Empfängerin ("Ihr Stück über X vom …"). Wenn kein echter Bezug bekannt ist: Einstieg weglassen statt heucheln — nie einen Bezug erfinden.
2. **Die Geschichte (2–3 Sätze):** Was ist neu, warum jetzt, warum für dieses Medium.
3. **Das Angebot (1–2 Sätze):** Was konkret verfügbar ist — Interview, exklusive Zahlen, Besuch vor Ort, Bildmaterial.
4. **Call-to-Action + Deadline:** ein klarer nächster Schritt.
5. Signatur der Agentur; PM ggf. unterhalb der Signatur oder als Link — Anhänge nur, wenn das Medium sie laut Verteiler-Notiz akzeptiert.

### Schritt 3: Regeln
- Pro Empfänger:in eine individuelle Mail; bei Segment-Versand mindestens Einstieg und Relevanzsatz pro Medium variieren.
- Exklusivität ist binär: Was einem Medium exklusiv angeboten wurde, wird vor dessen Absage/Deadline niemandem sonst angeboten. Laufende Exklusiv-Angebote im Vorgangsordner protokollieren (`pitch-log.md`: Datum, Medium, Person, Status, Deadline).
- Sperrfristen nur nach Skill `embargo-und-sperrfrist`.
- Keine Follow-ups im Abstand < 3 Werktage; maximal ein Nachfass pro Pitch.
- **Versand nie automatisch**: Entwürfe werden dem Nutzer zur Freigabe vorgelegt; Versand nur nach explizitem Go, bevorzugt als E-Mail-Entwurf im Postfach des Nutzers.

### Schritt 4: Quality-Gates
`fakten-gate` (Behauptungen im Pitch) und `freigabe-gate` (Kurzform für Pitches: Empfänger korrekt? Exklusiv-Konflikt? No-Gos?) — dann erst Vorlage an den Nutzer.
