# Zusammenarbeit an der RRLA

Die RRLA entsteht gemeinsam, aber nicht ungeordnet. Dieses Dokument klärt
Verantwortung, Arbeitsfluss und Qualitätsregeln.

## Rollen im Architekturprozess

### Hauptstammleitung: Architekturverantwortung

Die Hauptstammleitung verantwortet:

- Methodik und Reihenfolge
- Big Picture und Konsistenz
- Templates und Visualisierungen
- Moderation und Versionierung
- Vorbereitung von Arbeitsrahmen und Leitfragen
- Sicherung von Entscheidungen und Konsequenzen

Sie ist Architektin des Prozesses, nicht alleinige Autorin der Inhalte.

### SLK: Architecture Review Board und Inhaltsentwicklung

Der SLK:

- prüft, ob Rahmen, Sprache und Reihenfolge praxistauglich sind,
- benennt blinde Flecken und Auswirkungen,
- entwickelt Vision, Kultur, Führungsverständnis und Modelle in Workshops mit,
- unterscheidet Beratung, Entscheidung und Information,
- trägt getroffene Entscheidungen nach außen mit.

### Fachleute und Betroffene

Sie werden hinzugezogen, wenn Erfahrung aus einer Domain, einem Projekt oder
einem Prozess benötigt wird. Wer betroffen ist, soll gehört werden; wer das
Mandat trägt, entscheidet innerhalb der vereinbarten Leitplanken.

## Arbeitsfluss

1. **Beobachtung:** Was ist konkret wahrnehmbar?
2. **Spannungsfeld:** Welche berechtigten Ziele stehen miteinander in Spannung?
3. **Leitfrage:** Was müssen wir verstehen oder entscheiden?
4. **Workshop:** Welche Perspektiven und Erkenntnisse entstehen gemeinsam?
5. **Entwurf:** Welche Architektur könnte die Erkenntnisse tragen?
6. **Entscheidung:** Wer entscheidet was, warum und mit welchen Konsequenzen?
7. **Pilot und Review:** Bewährt sich die Entscheidung in der Praxis?

Kein Schritt wird nur deshalb übersprungen, weil bereits eine bevorzugte Lösung
existiert.

## Sprachliche Trennung

| Begriff | Bedeutung | Beispiel |
|---|---|---|
| Tatsache | überprüfbare Information | Der SLK hat 13 Mitglieder. |
| Beobachtung | wertungsfreie Wahrnehmung | Operative Themen stehen regelmäßig auf der SLK-Agenda. |
| Deutung | mögliche Erklärung | Unklare Mandate könnten operative Rückfragen fördern. |
| Hypothese | bewusst zu prüfende Annahme | Domain-Owner könnten den SLK entlasten. |
| Entwurf | zusammenhängender Lösungsvorschlag | Aufgaben und Entscheidungsräume einer Domain sind skizziert. |
| Entscheidung | autorisierte Festlegung | Ein ADR nennt Mandat, Begründung und Konsequenzen. |

## Statuswerte

- `Arbeitsgrundlage`: vorbereitet für Diskussion oder Workshop
- `In Arbeit`: wird gemeinsam bearbeitet
- `Entwurf`: erste zusammenhängende Architektur liegt vor
- `In Review`: zuständiger Kreis prüft den Entwurf
- `Akzeptiert`: autorisierte Entscheidung
- `Pilot`: wird befristet erprobt
- `Eingeführt`: ist gelebte Arbeitsweise
- `Ersetzt`: durch eine neuere Entscheidung abgelöst
- `Verworfen`: bewusst nicht weiterverfolgt

## Dokumente erstellen oder ändern

- Für Arbeitsdokumente
  [`templates/working-document-template.md`](templates/working-document-template.md)
  verwenden.
- Für Workshops
  [`templates/workshop-template.md`](templates/workshop-template.md) verwenden.
- Beobachtungen und Antworten nicht vermischen.
- Gemeinsame Erkenntnisse erst nach dem Workshop eintragen.
- Entscheidungen mit einem ADR verlinken.
- Auswirkungen auf andere Kapitel und offene Fragen benennen.
- Klare deutsche Sprache verwenden; Fachbegriffe im
  [`Glossar`](appendix/GLOSSARY.md) erklären.

## Wann ein ADR nötig ist

Ein ADR ist sinnvoll, wenn eine Entscheidung:

- Architekturprozess oder Zuständigkeiten verändert,
- Rollen oder Entscheidungsrechte festlegt,
- Linie, Fachorganisation, Projekte oder Governance verändert,
- ein dauerhaftes Prinzip verbindlich macht,
- eine andere plausible Option ausschließt,
- später ohne ihren Kontext missverstanden werden könnte.

Workshop-Erkenntnisse sind noch kein ADR. Nutze
[`templates/adr-template.md`](templates/adr-template.md), sobald Mandat und
Entscheidung klar sind.

## GitHub ohne Zugangshürde

Nicht jedes SLK-Mitglied muss GitHub bedienen. Workshops dürfen analog oder in
vertrauten Werkzeugen stattfinden. Die Architekturverantwortlichen überführen
Ergebnisse anschließend transparent in dieses Repository und geben sie zum
Gegenlesen zurück.

## Dateinamen und Links

- Dateinamen: klein, deutsch oder etablierter Fachbegriff, mit Bindestrichen.
- Relative Markdown-Links verwenden.
- Mermaid nur einsetzen, wenn Beziehungen dadurch verständlicher werden.
- Keine parallelen Ablagen mit konkurrierenden „finalen“ Versionen anlegen.
