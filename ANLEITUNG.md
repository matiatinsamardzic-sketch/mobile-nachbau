# Mobile-Nachbau (Schulprojekt) – Anleitung

## Dateien
- index.html – die App
- manifest.webmanifest, sw.js – damit sie wie eine App installierbar ist
- apple-touch-icon.png, icon-192.png, icon-512.png – App-Icons

## Auf GitHub Pages veröffentlichen
1. Auf github.com einloggen, oben rechts **+ → New repository**, Name z.B. `mobile-nachbau`, **Public**, erstellen.
2. **Add file → Upload files**, alle Dateien aus diesem Ordner hineinziehen, **Commit changes**.
3. **Settings → Pages**: bei *Source* «Deploy from a branch», Branch `main`, Ordner `/ (root)`, **Save**.
4. Nach ca. 1 Minute ist die Seite unter `https://<dein-name>.github.io/mobile-nachbau/` erreichbar.

## Auf den Home-Bildschirm
- **iPhone (Safari):** Seite öffnen → Teilen-Symbol → «Zum Home-Bildschirm».
- **Android (Chrome):** Seite öffnen → ⋮-Menü → «Zum Startbildschirm hinzufügen» / «App installieren».

## Hinweise
- Fahrplan, Abfahrtstabelle und Haltestellen auf der Karte sind echte Daten (transport.opendata.ch) und brauchen Internet.
- Für «Aktueller Standort» muss der Standortzugriff erlaubt werden.
- Name/E-Mail: Profil → Persönliche Daten. Alles wird nur lokal auf dem Handy gespeichert.
- SwissPass-Nummern, QR- und Barcode sind absichtlich Fantasiewerte mit «MUSTER»-Wasserzeichen – kein gültiger Fahrausweis.
