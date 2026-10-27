# JavaScript Academy

Eine deutschsprachige Lernumgebung, mit der du JavaScript Schritt für Schritt lernen und direkt im Browser ausprobieren kannst.

## Live-Demo

https://jguertler23.github.io/javascript-academy/

## Funktionen

- **42 Lektionen** – von JavaScript-Grundlagen bis zu Projektübungen.
- **Erklärungen und Beispiele** zum schrittweisen Lernen.
- **Code-Editor im Browser**, um JavaScript praktisch auszuprobieren.
- **Aufgaben und Quizfragen**, um Wissen zu überprüfen.
- **Lernfortschritt**, der lokal im Browser gespeichert wird.
- **Keine Anmeldung erforderlich.**

> Hinweis: Der Lernfortschritt wird lokal in deinem Browser gespeichert. Er ist nicht automatisch zwischen Geräten synchronisiert und kann beim Löschen der Browserdaten verloren gehen.

## Projektdateien

Die Anwendung besteht aus drei Hauptdateien im Repository-Stammverzeichnis:

- `index.html` – Einstiegspunkt der Webseite. Die Datei enthält die HTML-Struktur und bindet `style.css` sowie `main.js` ein.
- `style.css` – Gestaltung und responsives Layout der Lernoberfläche.
- `main.js` – Lektionen, Quizfragen und die interaktiven Funktionen der Academy, einschließlich der lokalen Speicherung des Lernfortschritts.

## Lokal starten

1. Lade das Repository als ZIP herunter.
2. Entpacke die ZIP-Datei.
3. Öffne `index.html` in einem aktuellen Browser.

Für die einfache lokale Nutzung ist keine Installation erforderlich.

## Entwicklung und Veröffentlichung

Das Projekt nutzt zwei Branches:

- `development` – Änderungen entwickeln und vor der Veröffentlichung testen.
- `main` – veröffentlichter Stand; GitHub Pages stellt diesen Branch als Live-Version bereit.

Für Änderungen gilt dieser Ablauf:

1. Änderungen auf `development` vornehmen.
2. `index.html` lokal in einem aktuellen Browser öffnen und die geänderten Funktionen vor dem Merge testen. Prüfe insbesondere, ob Lektionen angezeigt und gewechselt werden können, Code ausgeführt wird und Quiz sowie Fortschritt wie erwartet funktionieren.
3. Einen Pull Request von `development` nach `main` erstellen und die Änderungen prüfen lassen.
4. Den Pull Request erst nach erfolgreicher Prüfung in `main` zusammenführen.
5. Nach der Veröffentlichung die [Live-Version](https://jguertler23.github.io/javascript-academy/) im Browser öffnen und die betroffenen Funktionen prüfen. Kontrolliere, dass die Seite lädt, die Änderungen sichtbar sind und keine Fehler bei der Nutzung auftreten.

## Technologien

- HTML
- CSS
- JavaScript
- GitHub Pages

## Projektstatus

Die Academy wird weiterentwickelt. Neue Funktionen und Verbesserungen werden schrittweise ergänzt.

## Hinweis

Prüfe Änderungen vor dem Zusammenführen in `main`, damit die veröffentlichte Version funktionsfähig bleibt.