# LB 324

## Lokales Starten
1. pip install -r requirements.txt
2. flask run

## Aufgabe 2 Pre-commit installieren und nutzen
1. pip install pre-commit black pytest
2. pre-commit install
3. pre-commit install --hook-type pre-push
4. Bei jedem commit formatiert black automatisch.
5. Bei jedem push läuft pytest.

## Aufgabe 3 Pull Requests und Tests
1. Für jeden pull request auf den dev Ast werden die Tests ausgeführt.
2. Es werden keine weiteren Aktionen ausgeführt.

## Aufgabe 4 Passwortübertragung und Auslieferung
1. In Azure Web App unter Configuration ein Application setting erstellen.
2. Name PASSWORD
3. Wert dein GitHub Benutzername
4. In GitHub unter Settings Secrets and variables Actions das Secret AZURE_WEBAPP_PUBLISH_PROFILE anlegen.
5. Bei jedem merge in den main Ast erfolgt eine automatische Auslieferung auf Azure.

## Laufende Applikation
https://lb-324-eradbffabmbwh6hz.switzerlandnorth-01.azurewebsites.net/

## Administrative Vorgaben
1. Beispiel Projekt von Moodle laden.
2. Neue Ablage auf github.com anlegen. Name NameVornameLB-324. Öffentlich.
3. URL der Ablage im Moodle Formular abgeben.
4. Am Schluss das Projekt als Archiv von github.com herunterladen, das Archiv umbenennen und auf Moodle hochladen.
5. Wenn eine Aufgabe Dokumentation verlangt, hier eintragen.

## Branches
1. main entspricht der ausgelieferten Version.
2. dev enthält getesteten Code.
3. feature Äste für neue Arbeiten ausgehend von dev.

## .env
1. Datei .env im Projekt mit einer Zeile.
2. PASSWORD="einSehrGeheimesPasswort"
3. Für die Auslieferung den Wert ändern. Er soll gleich deinem GitHub Benutzernamen sein.
