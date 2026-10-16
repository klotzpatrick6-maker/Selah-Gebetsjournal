# Selah – Premium-Grundgerüst

Dies ist ein mobiler Web-App-Prototyp, der später am PC weiterentwickelt werden kann.

## Dateien
- `index.html` – Layout, Design und Funktionen
- `manifest.webmanifest` – Installierbarkeit als Web-App
- `sw.js` – Offline-Caching
- `icon.svg` – App-Symbol
- `README.md` – diese Anleitung

## Bereits enthalten
- Journal mit Datum, Gedanken, Bibelstelle, Gebet und nächstem Schritt
- Gebetsanliegen mit Status und Antwort-Rückblick
- Dankbarkeitstagebuch
- ausführliche Andacht mit Reflexionsfragen und Gebet
- Suche, Bearbeiten und Löschen von Einträgen
- JSON-Backup exportieren und importieren
- eine Minute Stille als Timer
- optionaler, synthetisch erzeugter kurzer Klangtest (kein Musikstück)
- responsive, mobilfreundliche Oberfläche und Basis-Offline-Unterstützung

## Wichtig
Prototyp, noch nicht app-store-fertig oder professionell geprüft. Einträge liegen unverschlüsselt im lokalen Browser-Speicher. Sie werden von dieser App nicht an einen Server gesendet, es gibt aber keine Cloud-Synchronisierung. Regelmäßig Backups erstellen. Der Code der GitHub-Pages-App ist öffentlich einsehbar. Für richtige Musik/Naturklänge später nur Audio mit klarer Lizenz verwenden. Vor Veröffentlichung sind Datenschutz, Barrierefreiheit, Tests, Backup/Restore und App-Store-Anforderungen zu prüfen.

## Auf dem PC weiterbauen
Die ZIP entpacken und den Ordner in Visual Studio Code öffnen. Alle Texte, Farben und Funktionen sind in `index.html` gebündelt; PWA-Metadaten liegen in `manifest.webmanifest`, Offline-Verhalten in `sw.js`. Für größere spätere Entwicklung empfiehlt sich, HTML/CSS/JavaScript in getrennte Dateien aufzuteilen und Tests einzurichten.
