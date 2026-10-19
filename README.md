# Mein Training – Version 1.4

Drei Trainingsprogramme (A, B, C) für zu Hause mit jeweils einzeln zugeordneten Bildern, Anleitungen, Wiederholungen und Sicherheitshinweisen. Wechsel zwischen den Programmen im Tab „Training“. Trainingstagebuch und JSON-Export enthalten; bisherige lokale Einträge unter `mein-training-v1` werden zusätzlich angezeigt.

## Installation / Aktualisierung

Alle Dateien aus diesem Paket **entpackt** ins Hauptverzeichnis von `ChJ22/-mein-training` hochladen und vorhandene Dateien überschreiben. Unter GitHub Pages Branch `main` und `/ (root)` verwenden. App-Adresse: https://chj22.github.io/-mein-training/ . Bereits installierte App nach dem Deployment neu starten; bei Cache-Problemen erst die Webseite in Safari aktualisieren. Vor dem Löschen der installierten App Trainingstagebuch als JSON exportieren.

## Hinweise

Bildmaterial sind zugeschnittene Übungsfelder aus dem freigegebenen Infografik-Entwurf. Illustrationen dienen zur Orientierung; die ausführlichen Anweisungen stehen **bei jeder einzelnen Übung**. Kein Ersatz für ärztliche oder physiotherapeutische Beratung. Bei Herzschrittmacher ist die Belastbarkeit individuell abzuklären.

## Neues App-Symbol (Version 1.4)

Das allgemeine Fitness-Icon mit zwei sportlichen Silhouetten ersetzt das bisherige T-Symbol. Enthalten sind `icon-192.png`, `icon-512.png` und `apple-touch-icon.png`. Die Manifest-Datei verwendet die neuen Icons, und der Service-Worker-Cache wurde auf Version 1.4 angehoben.

**Wichtig:** Alle Dateien im ZIP ins Repository-Hauptverzeichnis hochladen (nicht die ZIP selbst). Vorhandene Dateien ersetzen. iOS kann das alte Home-Bildschirm-Icon weiter anzeigen, bis der Home-Bildschirm-Eintrag entfernt und nach der Veröffentlichung neu hinzugefügt wird. Vor dem Entfernen einer bereits benutzten App die Trainingsdaten als JSON exportieren; lokale Daten können sonst verloren gehen.


## Version 1.5 – Trainingstagebuch
- Tagebucheinträge unabhängig von Trainingseinheiten anlegen (Datum, Typ, Schmerzstärke, Notiz).
- Gespeicherte Trainings und Tagebucheinträge gemeinsam anzeigen.
- Einzelne manuelle Tagebucheinträge löschen.
- Alle Einträge als JSON exportieren.
- Bestehende Einträge bleiben über den bisherigen lokalen Speicherschlüssel erhalten.
- Speicherung erfolgt ausschließlich lokal im jeweiligen Browser/App-Kontext; vor Neuinstallation oder Löschen der App Daten exportieren.

## Tagebuch-Export (Version 1.6)
Im Tagebuch „Trainingstagebuch als PDF speichern“ antippen. Im Druckdialog kann unter iOS die Druckvorschau über das Teilen-Menü als PDF in „Dateien“ gespeichert werden; unter Android „Als PDF speichern“ wählen. Die JSON-Datensicherung bleibt erhalten und kann über „Datensicherung wiederherstellen (JSON)“ wieder eingelesen werden. Die PDF ist zum Lesen, nicht zur Wiederherstellung gedacht. Daten werden weiterhin lokal im Browser gespeichert.
