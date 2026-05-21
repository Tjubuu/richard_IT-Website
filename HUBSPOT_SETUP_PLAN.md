# HubSpot Setup Plan

Stand: 2026-05-21

Dieses Dokument hält fest, wie HubSpot für richard_IT sinnvoll eingerichtet
werden soll, ohne die Website vorschnell mit Tracking, Formularen oder
externen Skripten zu verbinden.

## Grundsatz

HubSpot wird zunächst nur als internes CRM und Organisationswerkzeug genutzt.
Auf der Website wird HubSpot erst eingebunden, wenn Account Einrichtung,
Datenschutz, Cookie Consent und Zweck der Einbindung sauber geklärt sind.

## Aktueller Stand

| Punkt | Stand |
| --- | --- |
| HubSpot Account | vorhanden |
| Geschäftsmail | richard_IT@eclipso.eu |
| Account Hinweis | eclipso Mail Europe 148531682 |
| Website Einbindung | nein |
| Tracking Code auf Website | nein |
| HubSpot Formular auf Website | nein |
| HubSpot iframe auf Website | nein |
| HubSpot Link auf Kontaktseite | nein |

## Zielbild

HubSpot soll richard_IT zunächst bei folgenden Aufgaben unterstützen:

- Kontakte strukturiert verwalten
- einfache Gesprächsnotizen pflegen
- Anfragen und nächste Schritte nachhalten
- spätere Formular oder Newsletter Nutzung vorbereitet bewerten
- keine unnötige Tracking Infrastruktur erzeugen

## Phase 1: Account sauber einrichten

In HubSpot prüfen und setzen:

- Firmenname: richard_IT
- Geschäftsmail: richard_IT@eclipso.eu
- Sprache und Region passend einstellen
- Zeitzone passend einstellen
- eigenes Profil vervollständigen
- unnötige Beispiel oder Demo Daten entfernen, falls vorhanden
- Benutzer und Berechtigungen prüfen

## Phase 2: CRM minimal strukturieren

Zunächst nur eine schlanke Struktur verwenden:

- Kontakte
- Unternehmen
- Notizen
- Aufgaben
- Deals nur verwenden, wenn wirklich sinnvoll

Empfohlene einfache Kategorien:

- Interessent
- Kunde
- Partner
- Plattformkontakt
- Sonstiges

## Phase 3: Datenschutz und Verträge prüfen

Vor produktiver Nutzung mit personenbezogenen Daten prüfen:

- HubSpot Data Processing Agreement
- Account Datenschutz Einstellungen
- Lösch und Exportmöglichkeiten
- ob Kontakte aktiv eingewilligt haben oder eine andere Rechtsgrundlage besteht
- ob die Datenschutzerklärung angepasst werden muss

## Phase 4: Website Einbindung bewusst zurückstellen

Nicht einbauen, solange nicht ausdrücklich entschieden:

- HubSpot Tracking Code
- HubSpot Formular
- HubSpot Chat Widget
- HubSpot iframe
- HubSpot Cookie Banner

Eine spätere Einbindung erfordert vorher:

- klare Zweckentscheidung
- Datenschutztext aktualisieren
- Cookie und Consent Lösung prüfen
- technische Kontrolle auf script und iframe Tags
- erneute Veröffentlichungskontrolle

## Phase 5: Möglicher späterer Website Einsatz

Wenn HubSpot später auf der Website genutzt wird, dann vorzugsweise zuerst
mit einem klaren Kontaktformular für konkrete Anfragen. Tracking, Newsletter
und Chat Widgets bleiben zusätzliche Einzelentscheidungen.

## Pflegehinweis

HubSpot Änderungen werden nicht automatisch auf die Website übertragen.
Jede Website Einbindung muss als eigener Git Branch umgesetzt, geprüft,
committet und per Pull Request gemergt werden.

Vor jedem Merge prüfen:

- Datenschutz aktualisiert?
- Impressum unverändert korrekt?
- script Tags bewusst und dokumentiert?
- iframe Tags bewusst und dokumentiert?
- Cookie Consent erforderlich?
- PUBLICATION_REVIEW.md aktualisieren?
- ASSET_RIGHTS.md betroffen?
