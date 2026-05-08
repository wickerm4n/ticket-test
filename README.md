# Ticketverwaltung – GitHub Pages + Firebase

Diese Version ist für dein Repository `ticket-test` vorbereitet und enthält bereits die fertige Firebase-Web-Konfiguration.

## Ziel-URL

```text
https://wickerm4n.github.io/ticket-test/
```

## Enthaltene Dateien

```text
index.html
404.html
.nojekyll
style.css
app.js
firebase-config.js
firebase-rules.json
icon.svg
version.json
README.md
```

## Bereits eingetragen

In `firebase-config.js` ist bereits eingetragen:

```text
Projekt: ticketverwaltung-b5164
Realtime Database: https://ticketverwaltung-b5164-default-rtdb.europe-west1.firebasedatabase.app
GitHub-Pages-Basis: https://wickerm4n.github.io/ticket-test/
```

## Was du in Firebase noch machen musst

### 1. Anonymous Authentication aktivieren

Firebase Console:

```text
Authentication
→ Sign-in method
→ Anonymous
→ Aktivieren
→ Speichern
```

### 2. GitHub-Pages-Domain für Auth erlauben

Firebase Console:

```text
Authentication
→ Settings / Einstellungen
→ Authorized domains / Autorisierte Domains
→ Domain hinzufügen
→ wickerm4n.github.io
```

### 3. Realtime-Database-Regeln einfügen

Firebase Console:

```text
Realtime Database
→ Rules / Regeln
→ vorhandenen Inhalt komplett ersetzen
→ Inhalt aus firebase-rules.json einfügen
→ Veröffentlichen
```

Nicht dauerhaft offene Regeln wie `.read: true` / `.write: true` verwenden.

## GitHub Pages hochladen

Alle Dateien aus diesem ZIP direkt in den Root deines GitHub-Repositories `ticket-test` hochladen.

GitHub:

```text
Repository ticket-test
→ Settings
→ Pages
→ Deploy from branch
→ Branch: main
→ Folder: /root
→ Save
```

Danach kurz warten und öffnen:

```text
https://wickerm4n.github.io/ticket-test/
```

## Share-Funktion testen

1. Seite öffnen.
2. Falls nötig ein Ticket anlegen.
3. Teilen-Icon im Header anklicken.
4. Read-only-Link kopieren und in einem anderen Browser/Inkognito öffnen.
5. Prüfen: Anzeigen und CSV-Export ja, Bearbeiten/Löschen/Speichern nein.
6. Edit-Link kopieren und in einem anderen Browser/Inkognito öffnen.
7. Prüfen: Tickets hinzufügen/bearbeiten/löschen wird in beiden Fenstern synchronisiert.

## Sicherheit

Die Daten in `firebase-config.js` sind normale Firebase-Web-App-Konfiguration und kein Admin-Schlüssel.
Nicht öffentlich hochladen darfst du dagegen Service-Account-Dateien, private Schlüssel oder Tokens.
