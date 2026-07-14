# 08 Architecture Decision Records

ADRs dokumentieren wichtige Architekturentscheidungen.

Sie erklaeren nicht nur, was entschieden wurde, sondern warum. Das ist besonders
wichtig, wenn neue Leiter spaeter verstehen sollen, weshalb der Stamm so
arbeitet.

## Wann ein ADR noetig ist

Ein ADR ist sinnvoll, wenn eine Entscheidung:

- Rollen veraendert
- Entscheidungsrechte veraendert
- Gremien oder Meetings veraendert
- Domains einfuehrt
- Prozesse verbindlich macht
- Tools wie RRBase strukturell beeinflusst
- in zwei Jahren noch erklaert werden muss

## Nummerierung

Format:

`adr-0001-kurzer-titel.md`

Beispiele:

- `adr-0001-github-markdown-als-single-source-of-truth.md`
- `adr-0002-schichtenmodell-fuer-rrla.md`
- `adr-0003-slk-als-review-und-leitplankengremium.md`

## Statuswerte

- `Entwurf`
- `Akzeptiert`
- `Ersetzt`
- `Verworfen`

## Ablauf

1. Entscheidung als Entwurf anlegen.
2. Kontext und Optionen beschreiben.
3. Konsequenzen ehrlich benennen.
4. Entscheidung pruefen.
5. Status aktualisieren.
6. Relevante Dokumente verlinken.

## Template

Nutze [`../templates/adr-template.md`](../templates/adr-template.md).

## ADR Index

| ADR | Titel | Status |
|---|---|---|
| [`adr-0001-github-markdown-als-single-source-of-truth.md`](adr-0001-github-markdown-als-single-source-of-truth.md) | GitHub und Markdown als Single Source of Truth | Akzeptiert |
| [`adr-0002-schichtenmodell-fuer-rrla.md`](adr-0002-schichtenmodell-fuer-rrla.md) | Schichtenmodell fuer RRLA | Akzeptiert |
