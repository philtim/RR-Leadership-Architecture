# Zusammenarbeit an RRLA

Dieses Repository ist die Single Source of Truth fuer die Royal Rangers
Leadership Architecture.

Es soll einfach genug bleiben, dass es genutzt wird, und klar genug, dass
wichtige Entscheidungen spaeter nachvollziehbar sind.

## Rollen in der Erarbeitung

### Hauptstammleitung

Die Hauptstammleitung haelt das Big Picture.

Aufgaben:

- Zielarchitektur entwerfen
- Spannungen zwischen Bereichen erkennen
- Kultur und Leitplanken schuetzen
- Entscheidungen vorbereiten
- SLK-Feedback einarbeiten
- Architektur konsistent halten

### SLK

Der SLK ist Architecture Review Board, nicht Redaktionskreis fuer jedes Detail.

Aufgaben:

- Entwuerfe pruefen
- blinde Flecken benennen
- praktische Risiken sichtbar machen
- Leitplanken bestaetigen
- Entscheidungen mittragen

### Domain-Experten

Domain-Experten arbeiten konkrete Bereiche aus.

Beispiele:

- Material
- Kommunikation
- Medien
- Finanzen
- Ausbildung
- Veranstaltungen
- IT / RRBase

Sie entscheiden nicht das Gesamtmodell, sondern gestalten ihren Bereich innerhalb
der gemeinsamen Architektur.

## Arbeitsmodus

Wir arbeiten iterativ:

- `v0.1`: erster Entwurf der Hauptstammleitung
- `v0.2`: Review durch SLK
- `v0.3`: Schaerfung mit Domain-Experten
- `v1.0`: eingefuehrte und gelebte Version

Eine Datei muss nicht perfekt sein, um wertvoll zu sein. Sie muss klar zeigen,
was bereits entschieden ist und was noch offen ist.

## Statusbegriffe

Nutze diese Statuswerte einheitlich:

- `Entwurf`: Gedanke ist formuliert, aber noch nicht geprueft.
- `In Review`: Entwurf liegt beim SLK oder bei Domain-Experten.
- `Akzeptiert`: Entscheidung oder Inhalt ist beschlossen.
- `Pilot`: Wird testweise angewendet.
- `Eingefuehrt`: Ist offiziell Teil der Arbeitsweise.
- `Verworfen`: Wurde bewusst nicht weiterverfolgt.

## Schreibregeln

- Kurz, klar, konkret.
- Keine Management-Floskeln.
- Keine Loesung ohne erklaertes Warum.
- Unterscheide Beobachtung, Hypothese und Entscheidung.
- Verlinke relevante ADRs und offene Fragen.
- Formuliere so, dass neue Leiter es verstehen.

## Wann ein ADR noetig ist

Ein Architecture Decision Record ist noetig, wenn eine Entscheidung:

- Rollen oder Verantwortung veraendert
- Entscheidungsrechte veraendert
- Meetings oder Gremien veraendert
- eine Domain einfuehrt oder abschafft
- ein Werkzeug wie RRBase strukturell praegt
- spaeter erklaert werden koennen muss

Nutze dafuer `templates/adr-template.md`.

## Umgang mit offenen Fragen

Offene Fragen gehoeren nach `OPEN-QUESTIONS.md`.

Eine Frage wird nicht geloescht. Sie wird auf `beantwortet` gesetzt und mit dem
Dokument oder ADR verlinkt, in dem die Antwort steht.

## Dateibenennung

Markdown-Dateien werden klein geschrieben und mit Bindestrichen getrennt.

Beispiele:

- `vision-2035.md`
- `leadership-principles.md`
- `material.md`
- `adr-0001-single-source-of-truth.md`

## Mermaid

Diagramme werden als Mermaid direkt in Markdown gepflegt.

Diagramme sollen Klaerung schaffen, nicht beeindrucken. Wenn ein Text einfacher
ist als ein Diagramm, gewinnt der Text.
