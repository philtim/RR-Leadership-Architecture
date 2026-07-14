# 06 Tools

Werkzeuge unterstuetzen die Architektur. Sie ersetzen keine geklaerten Rollen,
Entscheidungswege oder Prozesse.

Diese Schicht uebersetzt die vorherigen Schichten in Anforderungen an Tools wie
RRBase, WhatsApp, Website, Cloud, Bildarchiv oder Inventarsystem.

## Zweck

- Tool-Entscheidungen aus der Architektur ableiten
- Kommunikationskanaele entlasten
- Wissen auffindbar machen
- Prozesse digital unterstuetzen
- RRBase fachlich sauber ausrichten

## Grundsatz

Werkzeuge folgen der Organisation.

Wenn unklar ist, wer entscheidet, hilft kein Tool. Wenn unklar ist, wer Owner
eines Prozesses ist, darf RRBase diesen Prozess noch nicht fest verdrahten.

## Relevante Werkzeuge

| Werkzeug | Moeglicher Zweck | Status |
|---|---|---|
| RRBase | Kommunikation, Handbuch, Rollen, Wissen, Logbuchpruefungen, Prozesse | im Aufbau |
| WhatsApp | kurzfristige Abstimmung und bestehende Gruppen | ueberlastet |
| Website | externe Information und Sichtbarkeit | veraltet |
| Cloud / Archiv | Medien, Dokumente, Vorlagen | zu klaeren |
| Inventarsystem | Materialbestand, Ausleihe, Wartung | zu klaeren |
| Instagram | Aussenwirkung und Zugehoerigkeit | DSGVO klaeren |

## Leitfragen

- Welches Problem soll das Werkzeug loesen?
- Welche Rolle oder Domain ist Owner?
- Welche Informationen gehoeren in das Werkzeug?
- Welche Informationen gehoeren bewusst nicht hinein?
- Welche Rechte und Rollen braucht das Werkzeug?
- Welche Prozesse werden unterstuetzt?
- Welche Risiken entstehen durch das Werkzeug?
- Was muss offline oder ohne technische Huerden funktionieren?

## RRBase Leitplanken

RRBase soll nicht das Organisationsproblem loesen. RRBase soll die geklaerte
Organisation abbilden.

Anforderungen an RRBase entstehen daher aus:

- Rollenmodell
- Entscheidungsmodell
- Domain-Katalog
- Prozesskatalog
- Kommunikationsmodell
- Wissensmanagement

## Ergebnisartefakte

Empfohlene Dateien:

- `tool-landscape.md`
- `rrbase-requirements.md`
- `communication-channels.md`
- `knowledge-management.md`
- `media-archive.md`

## Definition of Done

Diese Schicht ist ausreichend bearbeitet, wenn:

- jedes wichtige Werkzeug einem Zweck zugeordnet ist
- Tool-Owner oder Domain-Owner geklaert sind
- RRBase-Anforderungen aus Architektur und Prozessen abgeleitet sind
- WhatsApp-Kanaele entlastet und klarer getrennt werden koennen
- keine Tool-Idee ohne Owner und Prozess weiterverfolgt wird

## Naechster Schritt

Weiter mit [`07-roadmap`](../07-roadmap/README.md).
