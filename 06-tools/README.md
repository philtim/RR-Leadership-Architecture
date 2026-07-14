# 06 – Werkzeuge

Status: Nachgelagerter Arbeitsbereich

## Warum gibt es dieses Kapitel?

Werkzeuge unterstützen geklärte Verantwortung, Kommunikation, Wissen und
Prozesse. Sie dürfen ungeklärte Organisation nicht technisch festschreiben.

## Kontext

RRBase befindet sich im Aufbau. WhatsApp übernimmt viele verschiedene Zwecke;
Website, Medienarchiv und Inventarsystem benötigen Klärung. Tool-Anforderungen
werden erst aus Führungs-, Rollen- und Prozessentscheidungen abgeleitet.

## Beobachtungen

- Informationen erreichen Eltern nicht immer zuverlässig.
- WhatsApp ist Austauschkanal, Broadcast, Projektablage und Terminmedium zugleich.
- Medien liegen teilweise auf privaten Geräten.
- Materialbestand und Nutzungshinweise sind nicht zentral auffindbar.
- Neue Tools können für technisch weniger versierte Leitende eine Hürde sein.

## Spannungsfelder

- zentrale Verlässlichkeit ↔ einfache Nutzung
- Transparenz ↔ Datenschutz und Zugriffsbegrenzung
- digitale Effizienz ↔ Teilhabe ohne Technikbarriere
- ein System ↔ spezialisierte Werkzeuge

## Leitfragen

- Welches geklärte Problem soll das Werkzeug lösen?
- Welche Rolle oder Domain ist Owner?
- Welche Information ist verbindlich und wie erreicht sie die Zielgruppe?
- Welche Rollen, Rechte und Datenschutzregeln folgen aus der Architektur?
- Was muss auch ohne App funktionieren?
- Welche vorhandenen Kanäle werden dadurch ersetzt oder bewusst beibehalten?

## Gemeinsame Erkenntnisse

Noch offen.

## Architekturentwurf – Werkzeuglandschaft als Hypothese

| Werkzeug | Möglicher Zweck | Voraussetzung |
|---|---|---|
| RRBase | Rollen, Wissen, Kommunikation und Ranger-Prozesse unterstützen | geklärte Rollen und Prozesse |
| WhatsApp | kurzfristige Abstimmung und soziale Kommunikation | klare Kanalregeln |
| Website | verlässliche öffentliche Information | Kommunikations-Owner und Inhalte |
| Medienarchiv | gemeinsame, datenschutzgerechte Medienablage | Medien- und Rechtekonzept |
| Inventarsystem | Bestand, Ausleihe, Wartung und Dokumentation | Materialprozess und Owner |
| GitHub | RRLA-Architecture-Workspace und Organisationsgedächtnis | akzeptierte Methodik |

## Architekturentscheidung / ADR

GitHub ist als RRLA-Workspace entschieden. Alle anderen Tool-Entscheidungen
folgen später aus der Architektur. Siehe
[`ADR-0003`](../08-decisions/adr-0003-github-als-architecture-workspace.md).
