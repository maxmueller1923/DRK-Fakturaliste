# DRK Fakturaliste

Digitale Einsatzdokumentation für den DRK-Kreisverband Karlsruhe.

## Deployment auf GitHub Pages

1. **Neues Repository erstellen** auf github.com (z.B. `drk-fakturaliste`)
2. **Dateien hochladen**: `index.html`, `manifest.json` und optionale Icons
3. **GitHub Pages aktivieren**:
   - Repo → Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main`, Ordner: `/ (root)`
   - Save
4. Nach 1–2 Minuten erreichbar unter: `https://DEIN-USERNAME.github.io/drk-fakturaliste/`

## Auf dem iPhone als App speichern

1. URL in Safari öffnen
2. Teilen-Button (Quadrat mit Pfeil) antippen
3. "Zum Home-Bildschirm" wählen
4. Die App öffnet sich dann ohne Safari-UI im Vollbild

## App-Icons (optional)

Lege zwei PNG-Dateien im Repo ab:
- `icon-192.png` (192×192px) – App-Icon
- `icon-512.png` (512×512px) – Splash-Screen

Idealerweise ein rotes DRK-Kreuz auf weißem Hintergrund.

## Features

- Schichtbezeichnung per Dropdown (1A–1Z)
- Fahrzeugkennung + Besatzung
- Bis zu 14 Einsätze pro Schicht erfassen
- Einsätze nachträglich bearbeiten (Tippen auf Eintrag)
- Einsätze löschen
- Handgeschriebenes Nadok markieren
- PDF-Export im Original-Fakturaliste-Layout via Druck-Dialog
