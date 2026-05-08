# Ticketverwaltung

Eine einfache Web-App zur Verwaltung von Event- und Menü-Tickets.

Mit der Ticketverwaltung können Tickets schnell erstellt, bearbeitet, gesucht, ausgewählt, gelöscht und als CSV-Datei exportiert werden. Die App eignet sich für kleine Veranstaltungen, Bestellungen, Menüausgaben oder ähnliche Ticketlisten.

## Funktionen

- Tickets mit Ticketnummer, Name, Telefonnummer, Tickettyp, Menü und Preis verwalten
- Ticketliste durchsuchen und filtern
- einzelne Tickets bearbeiten oder löschen
- mehrere Tickets markieren und gesammelt löschen
- ausgewählte Tickets als CSV-Datei exportieren
- komplette Ticketliste als CSV-Datei exportieren
- dezente Hinweisbenachrichtigungen nach Aktionen
- optionale Bestätigungsdialoge mit „Nicht erneut anzeigen“
- Share-Funktion zum Teilen einer Ticketliste
- Read-only-Link für reine Ansicht
- Edit-Link für gemeinsames Bearbeiten
- automatische Synchronisierung geteilter Ticketlisten

## Nutzung

Die App kann direkt im Browser geöffnet werden:

```text
https://wickerm4n.github.io/ticket-test/
```

Zum Erstellen eines Tickets die gewünschten Daten in das Formular eintragen und speichern. Bereits vorhandene Tickets erscheinen darunter in der Ticketliste.

Über die Checkboxen können mehrere Tickets gleichzeitig ausgewählt werden. Sobald mindestens ein Ticket markiert ist, stehen Aktionen wie Löschen oder CSV-Export für die Auswahl zur Verfügung.

## Ticketliste teilen

Über das Teilen-Symbol im Header kann ein Share-Link erstellt werden.

Es gibt zwei Freigabearten:

```text
Read-only
```

Andere Personen können die Ticketliste ansehen, aber keine Tickets erstellen, bearbeiten oder löschen.

```text
Editierbar
```

Andere Personen können die geteilte Ticketliste gemeinsam bearbeiten. Änderungen werden bei verbundenen Nutzern automatisch aktualisiert.

## Datenschutz-Hinweis

Geteilte Ticketlisten sind über den jeweiligen Share-Link zugänglich. Der Link sollte daher nur an Personen weitergegeben werden, die die Ticketdaten sehen dürfen.
