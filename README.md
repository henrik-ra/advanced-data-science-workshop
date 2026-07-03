# Advanced Data Science Workshop (Microsoft Fabric)

Hands-on-Workshop zu **AI Functions** und **Data Science auf unstrukturierten Daten** in Microsoft Fabric.

## Struktur
- `tasks/` — Aufgaben-Notebooks (`w3_00` – `w3_04`). Kontext (Label-Listen, JSON-Schemas, Prompts, Parsing/Speichern) ist vorgegeben; offen ist nur der jeweilige `ai.*`-Aufruf.
- `solution/` — vollständige Lösungs-Notebooks (Referenz / Trainer-Hand).
- `wagon/` — lizenzgeprüfte Demobilder für den CV-Teaser, je 1 Bild pro Schadensklasse (`00_rost` … `05_kein_schaden`). Quellen & Lizenzen: `wagon/CREDITS.md` (Wikimedia Commons, CC0/Public Domain/CC BY(-SA)).

## Ablauf
1. `w3_00_setup` — erzeugt die Ausgangsdaten (Tabelle `asset_meldungen`) und lädt die Wagon-Fotos automatisch aus diesem Repo (`wagon/`) als ZIP.
2. `w3_01` – `w3_04` — die AI-Function-Aufgaben: Stammdaten heilen, Sentiment & Keywords, CV-Teaser, Data Science auf unstrukturierten Daten.

**Voraussetzung:** Ein Fabric-Lakehouse ist an die Notebooks angehängt.
