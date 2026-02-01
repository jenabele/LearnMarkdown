Sonntag, 1. Februar 2026
17:28

• Überschriften: Sie sind leicht zu erstellen – einfach ein paar Rauten (#) vor dem Text einfügen, um verschiedene Überschrift-Ebenen zu verwenden.
• Fettdruck und Kursivschrift: Fettschrift wird mit zwei Sternchen (**) oder zwei Unterstrichen (__) um den Text erstellt, Kursivschrift mit einem Sternchen oder Unterstrich.
• Listen: Erstellen Sie nummerierte oder unnummerierte Listen mit einfachen Symbolen wie Bindestrichen (-) oder Zahlen.
• Blockzitate: Verwenden Sie ein Größer-als-Zeichen (>) vor dem Text, um Zitate oder wichtige Aussagen hervorzuheben.
• Code-Blöcke: Code wird mit Rückwärtsapostrophen (`) hervorgehoben. Für längere Abschnitte verwenden Sie drei davon.


HTML vs. Markdown – vollständige Referenz (mit escaped HTML)

# 1. Überschriften & Textformatierung
Funktion	    | HTML‑Code (exakt)	                | Markdown‑Code
Überschrift 1	| <h1>Das ist eine Überschrift</h1>	| # Das ist eine Überschrift
Überschrift 2	| <h2>Das ist eine Überschrift</h2>	| ## Das ist eine Überschrift
Überschrift 3	| <h3>Das ist eine Überschrift</h3>	| ### Das ist eine Überschrift
Absatz	        | <p>Das ist ein Textabschnitt</p>	| (Text + Leerzeile)
Zeilenumbruch	| <br>	                            | Zwei Leerzeichen am Zeilenende
Fett	        | <strong>Text</strong>	            | **Text**
Kursiv	        | <em>Text</em>	                    | *Text*
Fett + Kursiv	| <strong><em>Text</em></strong>	| ***Text***
Durchgestrichen	| <del>Text</del>	                | ~~Text~~
Hochgestellt	| Text<sup>2</sup>	                | Nicht nativ
Tiefgestellt	| Text<sub>2</sub>	                | Nicht nativ

# 2. Links & Medien
Funktion	    | HTML‑Code (exakt)	                                    | Markdown‑Code
Link	        | <a href="https://example.com">Link</a>	            | [Link](https://example.com)
Link mit Titel	| <a href="url" title="Titel">Link</a>	                | [Link](url "Titel")
Bild	        | <img src="bild.jpg" alt="Beschreibung">	            | ![Beschreibung](bild.jpg)
Bild mit Titel	| <img src="bild.jpg" alt="Beschreibung" title="Titel">	| ![Beschreibung](bild.jpg "Titel")

# 3. Listen
Funktion	        | HTML‑Code (exakt)	                        | Markdown‑Code
Ungeordnete Liste	| <ul><li>Eintrag</li></ul>	                | - Eintrag
Geordnete Liste	    | <ol><li>Eintrag</li></ol>	                | 1. Eintrag
Verschachtelt	    | <ul><li>A<ul><li>B</li></ul></li></ul>	| - A
                                                                | - B
Aufgabenliste (GFM)	—	                                        | - [ ] offen
                                                                | - [x] fertig

# 4. Code & Zitate
Funktion	            | HTML‑Code (exakt)	                                | Markdown‑Code
Inline‑Code	            | <code>Code</code>	                                | `Code`
Codeblock	            | <pre><code>Code</code></pre>	                    | Code
Codeblock mit Sprache	| <pre><code class="language-js">...</code></pre>	| js …
Blockzitat	            | <blockquote>Zitat</blockquote>	                | > Zitat
Mehrzeiliges Zitat	    | <blockquote><p>...</p></blockquote>	            | > Zeile 1
                                                                            | > Zeile 2

# 5. Tabellen
Funktion	        | HTML‑Code (exakt)	                                Markdown‑Code
Tabelle	            | <table><tr><th>A</th><td>B</td></tr></table>`	    | -|	
Links ausgerichtet	| <th style="text-align:left">A</th>	            | :---
Zentriert	        | <th style="text-align:center">A</th>	            | :---:
Rechts ausgerichtet	| <th style="text-align:right">A</th>	            |  ---:

# 6. Struktur & Layout
Funktion	        | HTML‑Code (exakt)	    | Markdown‑Code
Block / Bereich	    | <div>Bereich</div>	| (nicht vorhanden)
Inline‑Bereich	    | <span>Text</span>	    | (nicht vorhanden)
Horizontale Linie	| <hr>	                | ---
Kommentar	        | <!-- Kommentar -->	| Nicht nativ

# 7. Semantische HTML‑Tags
HTML‑Tag (exakt)	    | Bedeutung	      | Markdown‑Alternative
<header>...</header>	| Kopfbereich	  | Keine
<footer>...</footer>	| Fußbereich	  | Keine
<section>...</section>	| Abschnitt	      | Keine
<article>...</article>	| Inhaltseinheit  | Keine
<nav>...</nav>	        | Navigation	  | Keine
<main>...</main>	    | Hauptinhalt	  | Keine
<aside>...</aside>	    | Seiteninhalt	  | Keine

# 8. Formulare (nur HTML)
Markdown unterstützt keine Formulare.

# Hier die wichtigsten HTML‑Elemente:

Element	        | HTML‑Code (exakt)
Formular	    | <form action="/send" method="post">...</form>
Textfeld	    | <input type="text" name="name">
Passwortfeld	| <input type="password" name="pwd">
Checkbox	    | <input type="checkbox" checked>
Radiobutton	    | <input type="radio" name="x">
Button	        | <button>Klick</button>
Dropdown	    | <select><option>A</option></select>

# 9. GitHub‑Flavored Markdown (GFM)
Funktion	                | HTML‑Code (exakt)	   | Markdown‑Code
Aufgabenliste	            |  —	               | - [ ] offen
                            |                      | - [x] fertig
Tabellen erweitert	        |  —	               | GFM‑Tabellen
Inline‑HTML	                | Wird gerendert	   | Text
Codezeilen hervorheben	    |  —	               |  js
                                                   | console.log("Hi")



# 10. Kompaktes Cheat‑Sheet


# Markdown kurz & knapp
Code
# H1
## H2
**fett**
*kursiv*
~~durchgestrichen~~
`inline code`
> Zitat
- Liste
1. Liste
![Alt](bild.jpg)
[Link](url)
| A | B |
|---|---|


# HTML kurz & knapp
Code
<h1>Überschrift</h1>
<p>Absatz</p>
<strong>fett</strong>
<em>kursiv</em>
<del>durchgestrichen</del>
<code>inline</code>
<blockquote>Zitat</blockquote>
<ul><li>Liste</li></ul>
<img src="bild.jpg" alt="Alt">
<a href="url">Link</a>
<table><tr><th>A</th><td>B</td></tr></table>

************************


# Ein Markdown Dokument
Ein Markdown Dokument ist simpel und einfach.

Der Text lässt sich direkt mit einfachen Zeichen formatieren.
Es gibt **fetten Text**, *kursiven Text* oder auch [Verlinkungen](https://google.de).

Noch interessanter ist das Einfügen von Bildern:
![alt text](https://sandmann.co/wp-content/uploads/Was-ist-Markdown-Cover.jpg)

## Text formatieren mit Leichtigkeit

Mit Markdown lässt sich Text sehr einfach formatieren, ohne den Schreibfluss zu unterbrechen. Perfekt für Vielschreiber.


# Markdown-Syntax-Beispiele:

Element: Überschrift
Syntax: # H1
Beispiel: # Dies ist eine Überschrift 1

Element: Fettdruck
Syntax: **Text**
Beispiel: **Dies ist fetter Text**

Element: Kursivschrift
Syntax: *Text* 
Beispiel: *Dies ist kursiver Text*

Element: Liste (ungeordnet)
Syntax: – Element
Beispiel: – Punkt Eins
– Punkt Zwei

Element: Tabelle
Syntax: | -> für Spalten
Syntax: - -> für Zeilen
Beispiel: 

| Name           | Alter | Stadt          |
|----------------|-------|----------------|
| Jennifer Abele | 28    | Mutlangen      |
| Dietmar Abele  | 34    | Mutlangen      |
| Max Mustermann | 22    | Musterstadt    |


