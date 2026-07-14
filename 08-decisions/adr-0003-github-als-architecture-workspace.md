# ADR-0003: GitHub als Architecture Workspace und Organisationsgedächtnis

Status: Akzeptiert
Datum: 2026-07-14
Entscheidungsverantwortung: Hauptstammleitung

## Kontext

RRLA ist kein fertiges Handbuch. Arbeitsgrundlagen, Workshop-Ergebnisse,
Entwürfe und Entscheidungen müssen trotzdem versioniert, verknüpft und für
spätere Leitende nachvollziehbar bleiben.

## Entscheidung

GitHub ist der zentrale Architecture Workspace und das Organisationsgedächtnis
der RRLA. Das Repository enthält:

- Methodik und Arbeitsrahmen,
- Beobachtungen, Spannungsfelder und Leitfragen,
- Workshop-Unterlagen und konsolidierte Erkenntnisse,
- Architekturentwürfe,
- ADRs einschließlich ersetzter Entscheidungen,
- Roadmap, Backlog, Vorlagen und Glossar.

Workshop-Teilnahme setzt keine GitHub-Kenntnis voraus. Ergebnisse können analog
entstehen und werden anschließend transparent übertragen und zum Gegenlesen
zurückgegeben.

## Betrachtete Optionen

### GitHub nur als fertige Dokumentationsablage

Vorteil: übersichtliche Endergebnisse.
Nachteil: Denkweg, Unsicherheiten und Alternativen gehen verloren.

### GitHub als exklusives Kollaborationswerkzeug für alle

Vorteil: direkte Versionierung.
Nachteil: unnötige technische Zugangshürde für den SLK.

### GitHub als Architecture Workspace mit zugänglichen Workshop-Formaten

Vorteil: nachvollziehbares Gedächtnis ohne erzwungene Tool-Nutzung.
Nachteil: Architekturverantwortliche müssen Ergebnisse sorgfältig übertragen.

## Begründung

Die gewählte Option verbindet Versionierung und Nachvollziehbarkeit mit einer
Arbeitsweise, die Menschen nicht wegen eines Werkzeugs ausschließt.

## Konsequenzen

- Arbeitsdokumente dürfen ausdrücklich unfertig sein.
- Status und Dokumenttyp müssen klar erkennbar sein.
- Historische ADRs werden ersetzt, nicht still überschrieben.
- Workshop-Ergebnisse werden zeitnah zurückgespiegelt.
- Es darf keine konkurrierende „finale“ RRLA-Ablage geben.

## Review

Nach zwei SLK-Workshops prüfen: Ist die Rückspiegelung verständlich und schnell
genug? Entsteht eine unnötige GitHub-Hürde?
