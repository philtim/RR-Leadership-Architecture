# ADR-0002: Schichtenmodell fuer RRLA

Status: Akzeptiert
Datum: 2026-07-14
Owner: Hauptstammleitung

## Kontext

Der Stamm hat viele gleichzeitige Baustellen:

- Meetings
- Entscheidungswege
- Material
- Kommunikation
- Medien
- RRBase
- Finanzen
- Leiterentwicklung

Wenn diese Themen isoliert geloest werden, entsteht Aktionismus. Es braucht ein
Big Picture, aus dem kleinere Schritte abgeleitet werden koennen.

## Entscheidung

RRLA wird in Schichten entwickelt:

1. Mission
2. Vision
3. Kultur
4. Architekturprinzipien
5. Operating Model
6. Domains
7. Prozesse
8. Werkzeuge
9. Roadmap

Die Bearbeitung folgt dieser Reihenfolge. Offene Fragen aus spaeteren Schichten
werden notiert, aber nicht vorschnell geloest.

## Optionen

### Option A: Sofort die dringendsten Probleme loesen

Vorteile:

- schnelle Entlastung
- sichtbare Bewegung

Nachteile:

- Gefahr von Einzelmassnahmen
- keine gemeinsame Zielarchitektur
- spaetere Kollisionen wahrscheinlich

### Option B: Schichtenmodell

Vorteile:

- Big Picture bleibt fuehrend
- jede Massnahme kann zur Zielarchitektur zurueckverfolgt werden
- RRBase entsteht aus Organisation und Prozessen
- SLK-Review wird strukturierter

Nachteile:

- braucht Geduld
- akute Schmerzen muessen teilweise bewusst geparkt werden
- Hauptstammleitung muss die Architekturarbeit konsequent fuehren

## Begruendung

Das Schichtenmodell entspricht der Denkweise einer Enterprise Architecture und
passt zur beschriebenen architektonischen Arbeitsweise der Hauptstammleitung.

Es verhindert, dass ein Werkzeug, ein Meeting oder ein einzelnes Problem die
Gesamtarchitektur dominiert.

## Konsequenzen

Was wird besser:

- Massnahmen bekommen Kontext.
- Diskussionen koennen auf die passende Ebene verwiesen werden.
- Der SLK kann gezielter reviewen.
- Domain-Experten bekommen spaeter klare Leitplanken.

Was wird schwieriger:

- Nicht jede gute Idee wird sofort umgesetzt.
- Es braucht Disziplin, Themen nicht zu frueh zu vermischen.

## Auswirkungen

Betroffen:

- gesamte Repository-Struktur
- `START-HERE.md`
- `06-tools`
- `07-roadmap`

## Review

Review nach Abschluss von Mission, Vision und Kultur.
