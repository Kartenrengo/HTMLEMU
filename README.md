# Handheld

Ein Emulator für Game Boy, Game Boy Color und Game Boy Advance, der komplett in einer einzigen HTML-Datei läuft. Keine Installation, kein Server, kein Konto. Läuft im Browser und auf dem iPhone (auch als lokale Datei in Apps wie Sitecase).

## Funktionen

- Spielebibliothek mit Coverbildern (Vorschau aus dem Spiel selbst)
- ZIP-Dateien werden direkt geöffnet
- Speicherstände (Battery-Saves) bleiben erhalten, auch nach dem Schließen der App
- Schnellspeichern und Laden
- Geschwindigkeit 1×, 2× und 3×
- Import und Export von Speicherständen (.sav)
- Steuerung per Touch oder Bluetooth-Controller

## Wichtig: Spiele

Diese Seite enthält **keine Spiele**. Du brauchst deine eigenen Dateien (ROMs) von Spielen, die du besitzt. Diese Dateien dürfen nicht öffentlich verteilt werden, bitte lade sie nirgendwo hoch.

Unterstützte Formate: `.gb`, `.gbc`, `.gba`, `.zip` (mit einer der Dateien darin).

Patch-Dateien (`.ips`, `.bps`, `.ups`) sind noch nicht anwendbar. Sie brauchen das Originalspiel und einen Patch-Schritt, der hier noch fehlt.

## Benutzung

1. `index.html` im Browser öffnen oder über die Adresse der Seite aufrufen.
2. Mit dem Plus-Symbol Spiele hinzufügen.
3. Spiel antippen zum Starten.

## Lizenz

Der Code dieser Seite steht unter der MIT-Lizenz. Siehe `LICENSE`.

### Drittanbieter-Software

Die Emulation nutzt den Core **mGBA** über das Projekt **EmulatorJS** (Version 4.2.3, `@emulatorjs/core-mgba`).

- mGBA steht unter der **GNU General Public License v3.0**.
- Quellcode von mGBA: https://github.com/mgba-emu/mgba
- Quellcode von EmulatorJS: https://github.com/EmulatorJS/EmulatorJS

Die Seite wird in der Form ausgeliefert, in der der Core eingebunden ist. Wer die Seite weitergibt, muss die GPL-Bedingungen für den Core einhalten, insbesondere den Zugang zum Quellcode bieten.

Dieses Projekt ist nicht mit Nintendo verbunden. „Game Boy“, „Game Boy Color“ und „Game Boy Advance“ sind Marken von Nintendo.
