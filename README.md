# Mein Training – Trainings-App (Version 1.1)

**Mein Training** ist eine kostenlose, installierbare Trainings-Web-App (Progressive Web App, PWA) für iOS und Android. Sie ist langfristig für verschiedene Trainingsprogramme zu Hause gedacht; derzeit ist das erste Programm **„Unterer Rücken – Stabilisierung“** enthalten.

## Funktionen

- Trainingsübersicht, Trainingsstart und Trainingstagebuch
- Fünf Übungen zur Stabilisierung des unteren Rückens
- **Je Übung ein eigenes Bild und eine Schritt-für-Schritt-Anleitung** statt nur eines gemeinsamen Trainingsplakats
- Wiederholungen beziehungsweise Haltezeiten und Abhaken der Übungen
- Dokumentation von Trainingseinheiten und Beschwerden
- Lokale Datenspeicherung und JSON-Export

## GitHub-Repository

Das tatsächlich angelegte Repository heißt **`ChJ22/-mein-training`** (mit führendem Bindestrich):

- **Repository:** https://github.com/ChJ22/-mein-training
- **Veröffentlichte App:** https://chj22.github.io/-mein-training/
- **Eigene Repositories anzeigen:** https://github.com/ChJ22?tab=repositories

**Hinweis zur GitHub-Navigation:** Die Ansicht **„My contributions“** mit dem Filter `contributed-by:@me` ist nicht zwingend die vollständige Liste eigener Repositories. Um das Projekt in der eigenen Repository-Liste zu sehen, das Profilbild öffnen und **Your repositories** wählen oder den Link oben verwenden. Nicht versehentlich ein neues Repository erstellen.

## Veröffentlichung und Aktualisierung über GitHub Pages

1. Das bestehende Repository `ChJ22/-mein-training` öffnen.
2. Dateien aus diesem Paket **entpacken** und ins Hauptverzeichnis des Repositorys hochladen. Für Version 1.1 insbesondere `index.html` und `uebung-1.png` bis `uebung-5.png` aktualisieren; auch `sw.js`, `manifest.webmanifest` und diese README mit übernehmen.
3. Vorhandene Dateien beim Aktualisieren ersetzen beziehungsweise über die GitHub-Oberfläche einzeln bearbeiten/hochladen; keine doppelten Dateien in einem Unterordner anlegen. Änderungen mit **Commit changes** speichern.
4. Unter **Settings → Pages → Build and deployment**: **Deploy from a branch**, Branch **main**, Ordner **/(root)** auswählen und speichern (falls noch nicht geschehen).
5. Nach der Veröffentlichung die App-Adresse oben öffnen und die Änderungen prüfen. Eventuell muss die installierte Web-App neu gestartet oder ihr Cache aktualisiert werden.

## Installation auf dem Smartphone

- **iPhone:** Die veröffentlichte App in **Safari** öffnen. Das Safari-Menü neben der Adressleiste öffnen, **Teilen** wählen, dann **Zum Home-Bildschirm** und gegebenenfalls **Als Web-App öffnen** aktivieren.
- **Android:** Die veröffentlichte App in Chrome öffnen und **App installieren** beziehungsweise **Zum Startbildschirm hinzufügen** wählen.

Die App wird als Web-App installiert; es ist weder ein Apple-Developer-Konto noch ein App-Store-Eintrag erforderlich.

## Fehlerbehebung: weißer Bildschirm

Falls die installierte App nur einen weißen Bildschirm zeigt, zuerst die URL in Safari öffnen und testen. Wenn die Webseite funktioniert, können ein veralteter Offline-Cache, die Start-URL oder die Service-Worker-Konfiguration verantwortlich sein. Vor dem Löschen der installierten App **Trainingsdaten exportieren**, sofern bereits Daten vorhanden sind; beim Löschen können lokal gespeicherte Daten verloren gehen.

## Daten und Datenschutz

Trainingseinträge werden lokal im Browser beziehungsweise in der installierten Web-App mit `localStorage` gespeichert, **nicht** in GitHub. Ein JSON-Export ist vorgesehen. Es gibt noch keine Benutzerkonten, Synchronisierung oder automatische Cloud-Sicherung. Ein öffentliches GitHub-Repository veröffentlicht den **Quellcode**, nicht automatisch die lokal gespeicherten Trainingsdaten.

## Gesundheitshinweis

Die Übungen sind allgemeine Trainingsvorschläge, keine individuell abgestimmte Therapie. Nur kontrolliert und im tolerierbaren Bereich trainieren; bei deutlich zunehmenden Schmerzen oder neurologischen Symptomen abbrechen und medizinischen Rat einholen.
