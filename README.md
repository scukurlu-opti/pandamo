# Pandamo

**Find your calm.** — Tägliche Bewegungseinheiten bei Morbus Bechterew: Beweglichkeit, Atmung, Kraft und Ausdauer, von einem animierten Panda vorgeführt.

Eine einzelne HTML-Datei, keine Abhängigkeiten, kein Build, kein Server-Backend. Als Progressive Web App installierbar und nach dem ersten Laden offline nutzbar.

## Installieren (iPhone)

1. Die Seite in **Safari** öffnen.
2. Teilen-Symbol → **„Zum Home-Bildschirm"**.
3. Pandamo startet danach im Vollbild mit eigenem Icon.

## Inhalt

- **12 Programme** für zu Hause (Stuhl, Mini-Hanteln, Sportband), fürs Studio und fürs Laufen — inklusive „Sanfter Tag" für Schubphasen.
- **28 Übungen** mit Anleitung, Atemführung und Begründung, jeweils animiert in einer von sechs Haltungen (Sitz, Stand, Vierfüßler, Rücken-, Bauchlage, Laufen).
- **Wochenplan**, Tages-Reihe und Verlauf: Minuten pro Tag, Morgensteifigkeit, Hinterkopf-Wand-Abstand und Atembreite.
- **Laufen**: Laufband mit Steigung (Standard 4,5 km/h bei 8–10 %) oder draußen, immer mit Aufwärmen und Dehnen drumherum.

## Daten

Alles liegt ausschließlich im `localStorage` des jeweiligen Geräts. Es gibt keinen Server, keine Konten, keine Übertragung nach außen.

## Dateien

| Datei | Zweck |
| --- | --- |
| `index.html` | die komplette App (Stile, Panda-Rigs, Logik) |
| `sw.js` | Service Worker für den Offline-Betrieb |
| `manifest.webmanifest` | Name, Farben, Icons für die Installation |
| `icon-*.png`, `apple-touch-icon.png` | App-Icons |

## Hinweis

Pandamo ersetzt keine ärztliche Behandlung und keine Physiotherapie. Ziehen darf es, schmerzen nicht.
