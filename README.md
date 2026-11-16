# LHundG-Schnellprüfung

Web-App zur ersten Einordnung eines Hundes nach dem Landeshundegesetz NRW (LHundG NRW):
gefährlicher Hund (§ 3 Abs. 2 / Abs. 3), Hund bestimmter Rasse (§ 10), großer Hund (§ 11) oder sonstiger Hund (§ 2),
jeweils mit Subsumtion, Pflichtenliste mit Fundstellen und Hinweisen aus Verwaltungsvorschrift und Rechtsprechung.

Rechtsstand: LHundG NRW i.d.F. ab 27.09.2016; VV LHundG zuletzt geändert durch RdErl. v. 30.09.2026 (MB.NRW 2026 Nr. 281).
Arbeitshilfe, ersetzt nicht die Prüfung am amtlichen Normtext.

## Dateien

- `index.html` – die App (eine Datei, kein Build nötig)
- `manifest.webmanifest`, `icons/` – Installation auf dem Home-Bildschirm
- `sw.js` – Offline-Nutzung; bei Änderungen an der App die Versionsnummer `CACHE` erhöhen

## Veröffentlichen mit GitHub Pages

Settings → Pages → „Deploy from a branch“ → Branch `main`, Ordner `/ (root)` → Save.
Nach ein bis zwei Minuten ist die App unter `https://<benutzername>.github.io/<repository>/` erreichbar.
