# ADR-0001: GitHub und Markdown als Single Source of Truth

Status: Akzeptiert
Datum: 2026-07-14
Owner: Hauptstammleitung

## Kontext

RRLA soll nicht als lose Sammlung von Notizen, Chatverlaeufen oder
Office-Dokumenten entstehen. Die Architektur soll versioniert,
nachvollziehbar, iterativ und spaeter fuer mehrere Beteiligte bearbeitbar sein.

Gleichzeitig darf die Dokumentation nicht so komplex werden, dass sie im
ehrenamtlichen Kontext nicht mehr gepflegt wird.

## Entscheidung

RRLA wird in GitHub als Markdown-Dokumentation gepflegt.

GitHub ist die Single Source of Truth fuer:

- Zielarchitektur
- offene Fragen
- Architekturentscheidungen
- Roadmap und Backlog
- Templates
- Glossar

## Optionen

### Option A: Google Drive

Vorteile:

- vielen vertraut
- einfache gemeinsame Bearbeitung
- niedrige Einstiegshuerde

Nachteile:

- Versionierung und Architekturentscheidungen weniger sauber
- schnell unklare Dokumentvarianten
- spaetere Integration mit RRBase schwieriger

### Option B: GitHub und Markdown

Vorteile:

- klare Versionierung
- nachvollziehbare Aenderungen
- gute Strukturierbarkeit
- ADRs und Backlog passen natuerlich dazu
- spaeter gut mit RRBase oder Website integrierbar

Nachteile:

- fuer nicht-technische Personen erklaerungsbeduerftig
- braucht einfache Arbeitsregeln

## Begruendung

Philipp denkt und arbeitet stark architektonisch. GitHub und Markdown passen zu
einer iterativen Architekturarbeit, ohne proprietaere Dokumentformate zu
erzwingen.

Der technische Anspruch wird durch klare Templates und einfache Schreibregeln
begrenzt.

## Konsequenzen

Was wird besser:

- Entscheidungen sind nachvollziehbar.
- Struktur und Versionen bleiben sauber.
- Spaetere Mitarbeit im SLK oder mit Domain-Experten ist steuerbar.
- RRBase kann spaeter Inhalte oder Prinzipien uebernehmen.

Was wird schwieriger:

- Der Einstieg fuer nicht-technische Leiter muss begleitet werden.
- GitHub darf nicht zur Huerde fuer Feedback werden.
- Fuer den SLK braucht es eventuell exportierte oder vorbereitete Review-Dokumente.

## Auswirkungen

Betroffen:

- `README.md`
- `CONTRIBUTING.md`
- `START-HERE.md`
- `templates`
- `08-adr`

## Review

Review nach dem ersten SLK-Feedback zur Version 0.1.
