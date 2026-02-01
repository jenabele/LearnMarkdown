Eigene URL Seite erstellen
https://jenabele.github.io/LearnMarkdown/

mit Page, dafür wird eine index.md im /root - Verzeichnis benötigt

📘 GitHub Pages einrichten – vollständige Anleitung
Diese Anleitung erklärt Schritt für Schritt, wie du aus einem GitHub‑Repository eine funktionierende GitHub‑Pages‑Webseite erzeugst.

✅ 1. Repository öffentlich machen
GitHub Pages funktioniert nur, wenn das Repository public ist.

So stellst du das ein:

Repository öffnen

Settings

Ganz unten: Danger Zone

Change repository visibility

Auf Public stellen und bestätigen

✅ 2. Startdatei anlegen (index.md)
GitHub Pages benötigt eine Startdatei im Root‑Ordner des Repositories.

So erstellst du sie:

Add file → Create new file

Dateiname: index.md

Inhalt einfügen (z. B. eine Überschrift)

Commit directly to the main branch

Commit changes

Beispielinhalt:

markdown
# Willkommen auf meiner GitHub‑Pages‑Seite
✅ 3. Optional: eigenes CSS einbinden
Wenn du eigenes Styling verwenden möchtest, lege einen Ordner css/ an.

Ordner + Datei anlegen:

Add file → Create new file

Dateiname: css/style.css

CSS einfügen

Committen

CSS in index.md einbinden:

html
<link rel="stylesheet" href="css/style.css">
✅ 4. GitHub Pages aktivieren
Settings öffnen

Links: Pages

Unter „Build and deployment“:

Source: Deploy from branch

Branch: main

Folder: /root

GitHub baut die Seite automatisch.

✅ 5. GitHub‑Pages‑URL aufrufen
Die URL folgt immer diesem Muster:

Code
https://<username>.github.io/<repository-name>/
Beispiel für dieses Projekt:

Code
https://jenabele.github.io/LearnMarkdown/
Falls die Seite nicht sofort erscheint:
10–30 Sekunden warten und neu laden.

🔍 Häufige Fehler und Lösungen
Problem	Ursache	Lösung
„There isn't a GitHub Pages site here.“	Keine index.md im Root	Datei anlegen + committen
Seite bleibt leer	Datei nicht committed	Commit durchführen
CSS wird nicht geladen	Falscher Pfad	css/style.css prüfen
GitHub Pages lässt sich nicht aktivieren	Repo war privat	Repo auf public stellen
Falscher Ordner gewählt	/docs statt /root	In Pages‑Einstellungen korrigieren


# Weitere .md Datei Einbinden:
=> in index.md weitere .md Seite eingebunden: 
[Zur zweiten Seite](zweite-seite.md)

📁 3. Falls die Datei in einem Unterordner liegt
Beispiel: Datei liegt in /kapitel/seite1.md

Dann verlinkst du so:

markdown
[Kapitel 1](kapitel/seite1.md)

🌐 4. URL‑Struktur auf GitHub Pages
Wenn deine Seite unter:

Code
https://jenabele.github.io/LearnMarkdown/
liegt, dann ist die zweite Seite erreichbar unter:

Code
https://jenabele.github.io/LearnMarkdown/zweite-seite/
GitHub Pages wandelt .md automatisch in „saubere“ URLs um.

# **HTML escapen (wenn du HTML nur zeigen willst)
Das ist perfekt für eine Referenz wie deine.

Beispiel:

Code
&lt;h1&gt;Das ist eine Überschrift&lt;/h1&gt;**
