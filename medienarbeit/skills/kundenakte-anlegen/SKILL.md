---
name: kundenakte-anlegen
description: Legt für einen Agentur-Kunden eine strukturierte Kundenakte mit 3-Ebenen-Wissenssystem an (TEMPLATES, PRECEDENTS, KNOW-HOW) oder aktualisiert sie. IMMER verwenden, wenn ein neuer Kunde onboarded wird, ein Briefing eingeht, oder ein anderer Skill dieses Moduls keine Kundenakte findet. Trigger u.a. "neuer Kunde", "Kundenakte anlegen", "Briefing", "Onboarding".
---

# Kundenakte anlegen

Die Kundenakte ist das Fundament aller Medienarbeit-Skills. Ohne Kundenakte kein Text: Jeder Produktions-Skill (Pressemitteilung, Pitch-Mail, Pressemappe …) liest zuerst die Akte des betroffenen Kunden. Existiert keine, wird dieser Skill zuerst ausgeführt.

## Ablageort

```
kunden/<kunden-slug>/
├── KNOW-HOW.md          # Ebene 3: Kontextwissen über den Kunden
├── TEMPLATES/           # Ebene 1: Strukturvorlagen (kundenspezifisch angepasst)
├── PRECEDENTS/          # Ebene 2: frühere, freigegebene Texte als Formulierungsbenchmark
├── verteiler.md         # Medienkontakte und Verteiler-Segmente (siehe Skill verteiler-strategie)
└── projekte/            # laufende Vorgänge, je Vorgang ein Ordner
```

`<kunden-slug>` ist der Kundenname in kebab-case (z.B. `voltawerk`). Der Ordner `kunden/` liegt im Arbeitsverzeichnis der Agentur; falls die Agentur einen anderen Ablageort nutzt (Cloud-Laufwerk, Repo), dort dieselbe Struktur anlegen.

## Das 3-Ebenen-Wissenssystem

1. **TEMPLATES** — *Wie ist ein Dokument aufgebaut?* Strukturvorlagen für Pressemitteilung, Pitch-Mail, Pressemappe etc. Beim Anlegen zunächst leer lassen; die Produktions-Skills bringen Standard-Strukturen mit. Erst wenn ein Kunde abweichende Formate verlangt (z.B. eigener PM-Kopf, Pflicht-Boilerplate-Länge), hier eine kundenspezifische Vorlage ablegen — sie schlägt dann die Standard-Struktur des Skills.
2. **PRECEDENTS** — *Wie klingt dieser Kunde?* Jeder final freigegebene und veröffentlichte Text wird hier abgelegt (Dateiname: `JJJJ-MM-TT-<typ>-<thema>.md`). Produktions-Skills nutzen die 2–3 jüngsten passenden Precedents als Tonalitäts- und Formulierungsbenchmark. Precedents schlagen generische Stilregeln.
3. **KNOW-HOW.md** — *Was muss man über den Kunden wissen?* Siehe Struktur unten. Know-how schlägt alles: Ein No-Go im KNOW-HOW überstimmt jede noch so elegante Formulierung.

## Workflow

### Schritt 1: Vorhandenes prüfen
Prüfe, ob `kunden/<kunden-slug>/` bereits existiert. Wenn ja: nicht überschreiben, sondern gezielt ergänzen und dem Nutzer sagen, was ergänzt wurde.

### Schritt 2: Briefing-Interview
Fehlende Kerninformationen aktiv erfragen — nicht raten. Pflichtfelder für KNOW-HOW.md:

- **Unternehmen**: Rechtsform, Sitz, Gründungsjahr, Größe (Mitarbeitende, ggf. Umsatz falls kommunizierbar), Geschäftsmodell in einem Satz
- **Sprecher:innen**: Wer darf zitiert werden? Name, Funktion, bevorzugte Pronomen falls bekannt, Freigabe-Eigenheiten
- **Kernbotschaften**: 3–5 freigegebene Messages, wörtlich
- **Boilerplate**: der freigegebene "Über uns"-Absatz, wörtlich
- **Tonalität**: 3–5 Adjektive plus je ein Positiv-/Negativbeispiel
- **No-Gos**: verbotene Begriffe, Themen, Vergleiche, Wettbewerber-Nennungen
- **Freigabeprozess**: Wer gibt frei, in welcher Reihenfolge, welche Fristen
- **Zahlen-Politik**: Welche Zahlen sind öffentlich, welche tabu (Umsatz? Kundenzahlen? Funding?)
- **Ansprechpartner Agentur & Kunde**: Namen, Rollen, Kontaktweg

### Schritt 3: Akte schreiben
Lege die Ordnerstruktur an und schreibe `KNOW-HOW.md` mit genau diesen Abschnitten als H2-Überschriften. Jede Angabe, die der Kunde nur mündlich/per Mail geliefert hat, mit Datum versehen (`Stand: JJJJ-MM-TT`).

### Schritt 4: Bestandstexte einsammeln
Frage nach 2–5 früheren, freigegebenen Texten des Kunden (alte PMs, Website-Texte) und lege sie als erste PRECEDENTS ab. Ohne Precedents arbeiten die Produktions-Skills mit Standard-Tonalität und kennzeichnen das im Entwurf.

## Regeln

- Niemals Platzhalter-Fantasiewerte in KNOW-HOW.md schreiben. Fehlendes bleibt als `⚠️ OFFEN: …` markiert und wird beim nächsten Kundenkontakt erfragt.
- KNOW-HOW.md ist die einzige Quelle der Wahrheit für Boilerplate und Kernbotschaften. Produktions-Skills kopieren von dort, nie aus dem Gedächtnis.
- Personenbezogene Daten sparsam: nur geschäftliche Kontaktdaten, keine privaten.
