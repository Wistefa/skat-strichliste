# ♠ Skat Strichliste ♣

Strichliste für 4 Spieler mit automatischer Geberrotation, Spielwert-Berechnung und Bockrunden.

**Live:** https://wistefa.github.io/skat-strichliste  
**GitHub:** https://github.com/Wistefa/skat-strichliste

## Features

- **4 Spieler** – einer sitzt pro Runde aus (Geber rotiert automatisch)
- **Spielwert-Berechnung** – Farb, Grand, Null (Hand, Ouvert), Buben, Schneider/Schwarz
- **Bockrunden** – automatisch bei Niederlage, stapelbar, manuell auslösbar
- **Strichliste** – nur Minuszahlen werden eingetragen (Verlust-Prinzip)
- **Vorschau** – zeigt vor dem Eintragen wer welchen Strich bekommt
- **💾 FAB-Button** – Spieltag mit eigenem Dateinamen als JSON sichern; bei verbundenem iCloud-Datenpool direkt in den Ordner, sonst Download
- **iCloud Datenpool** – einmalig Ordner verbinden, danach wird nach jeder Runde automatisch `daten.json` gesichert (Chrome/Edge)
- **Laden** – JSON-Datei importieren und Spielstand vollständig wiederherstellen

## Technik

- Reines HTML/JS, kein Build-Prozess, kein Backend
- Responsive für iPhone und iPad (optimiert Juni 2026)
- Deployment via GitHub Pages

## Spieler

Hartmut, Thomas, Klaus, Wilfried

## Deployment

Änderungen direkt in `index.html` vornehmen und pushen — GitHub Pages deployt automatisch.
