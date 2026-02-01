Sonntag, 1. Februar 2026  
17:28

• Überschriften: Sie sind leicht zu erstellen – einfach ein paar Rauten (#) vor dem Text einfügen, um verschiedene Überschrift-Ebenen zu verwenden.  
• Fettdruck und Kursivschrift: Fettschrift wird mit zwei Sternchen (**) oder zwei Unterstrichen (__) um den Text erstellt, Kursivschrift mit einem Sternchen oder Unterstrich.  
• Listen: Erstellen Sie nummerierte oder unnummerierte Listen mit einfachen Symbolen wie Bindestrichen (-) oder Zahlen.  
• Blockzitate: Verwenden Sie ein Größer-als-Zeichen (>) vor dem Text, um Zitate oder wichtige Aussagen hervorzuheben.  
• Code-Blöcke: Code wird mit Rückwärtsapostrophen (`) hervorgehoben. Für längere Abschnitte verwenden Sie drei davon.  

---

# HTML vs. Markdown – vollständige Referenz (mit escaped HTML)

# 1. Überschriften & Textformatierung

| Funktion        | HTML‑Code (exakt)                                   | Markdown‑Code |
|-----------------|------------------------------------------------------|----------------|
| Überschrift 1   | &lt;h1&gt;Das ist eine Überschrift&lt;/h1&gt;       | # Das ist eine Überschrift |
| Überschrift 2   | &lt;h2&gt;Das ist eine Überschrift&lt;/h2&gt;       | ## Das ist eine Überschrift |
| Überschrift 3   | &lt;h3&gt;Das ist eine Überschrift&lt;/h3&gt;       | ### Das ist eine Überschrift |
| Absatz          | &lt;p&gt;Das ist ein Textabschnitt&lt;/p&gt;        | (Text + Leerzeile) |
| Zeilenumbruch   | &lt;br&gt;                                          | Zwei Leerzeichen am Zeilenende |
| Fett            | &lt;strong&gt;Text&lt;/strong&gt;                  | **Text** |
| Kursiv          | &lt;em&gt;Text&lt;/em&gt;                          | *Text* |
| Fett + Kursiv   | &lt;strong&gt;&lt;em&gt;Text&lt;/em&gt;&lt;/strong&gt; | ***Text*** |
| Durchgestrichen | &lt;del&gt;Text&lt;/del&gt;                        | ~~Text~~ |
| Hochgestellt    | Text&lt;sup&gt;2&lt;/sup&gt;                       | Nicht nativ |
| Tiefgestellt    | Text&lt;sub&gt;2&lt;/sub&gt;                       | Nicht nativ |

---

# 2. Links & Medien

| Funktion        | HTML‑Code (exakt)                                                      | Markdown‑Code |
|-----------------|-------------------------------------------------------------------------|----------------|
| Link            | &lt;a href="https://example.com"&gt;Link&lt;/a&gt;                     | [Link](https://example.com) |
| Link mit Titel  | &lt;a href="url" title="Titel"&gt;Link&lt;/a&gt;                       | [Link](url "Titel") |
| Bild            | &lt;img src="bild.jpg" alt="Beschreibung"&gt;                          | ![Beschreibung](bild.jpg) |
| Bild mit Titel  | &lt;img src="bild.jpg" alt="Beschreibung" title="Titel"&gt;            | ![Beschreibung](bild.jpg "Titel") |

---

# 3. Listen

| Funktion              | HTML‑Code (exakt)                                      | Markdown‑Code |
|-----------------------|---------------------------------------------------------|----------------|
| Ungeordnete Liste     | &lt;ul&gt;&lt;li&gt;Eintrag&lt;/li&gt;&lt;/ul&gt;     | - Eintrag |
| Geordnete Liste       | &lt;ol&gt;&lt;li&gt;Eintrag&lt;/li&gt;&lt;/ol&gt;     | 1. Eintrag |
| Verschachtelt         | &lt;ul&gt;&lt;li&gt;A&lt;ul&gt;&lt;li&gt;B&lt;/li&gt;&lt;/ul&gt;&lt;/li&gt;&lt;/ul&gt; | - A<br>&nbsp;&nbsp;- B |
| Aufgabenliste (GFM)   | —                                                       | - [ ] offen<br>- [x] fertig |

---

# 4. Code & Zitate

| Funktion                | HTML‑Code (exakt)                                              | Markdown‑Code |
|-------------------------|-----------------------------------------------------------------|----------------|
| Inline‑Code             | &lt;code&gt;Code&lt;/code&gt;                                   | `Code` |
| Codeblock               | &lt;pre&gt;&lt;code&gt;Code&lt;/code&gt;&lt;/pre&gt;           | ```<br>Code<br>``` |
| Codeblock mit Sprache   | &lt;pre&gt;&lt;code class="language-js"&gt;...&lt;/code&gt;&lt;/pre&gt; | ```js<br>...<br>``` |
| Blockzitat              | &lt;blockquote&gt;Zitat&lt;/blockquote&gt;                     | > Zitat |
| Mehrzeiliges Zitat      | &lt;blockquote&gt;&lt;p&gt;...&lt;/p&gt;&lt;/blockquote&gt;     | > Zeile 1<br>> Zeile 2 |

---

# 5. Tabellen

| Funktion            | HTML‑Code (exakt)                                              | Markdown‑Code |
|---------------------|-----------------------------------------------------------------|----------------|
| Tabelle             | &lt;table&gt;&lt;tr&gt;&lt;th&gt;A&lt;/th&gt;&lt;td&gt;B&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt; | \| A \| B \| |
| Links ausgerichtet  | &lt;th style="text-align:left"&gt;A&lt;/th&gt;                  | :--- |
| Zentriert           | &lt;th style="text-align:center"&gt;A&lt;/th&gt;                | :---: |
| Rechts ausgerichtet | &lt;th style="text-align:right"&gt;A&lt;/th&gt;                 | ---: |

---

# 6. Struktur & Layout

| Funktion            | HTML‑Code (exakt)               | Markdown‑Code |
|---------------------|----------------------------------|----------------|
| Block / Bereich     | &lt;div&gt;Bereich&lt;/div&gt; | (nicht vorhanden) |
| Inline‑Bereich      | &lt;span&gt;Text&lt;/span&gt; | (nicht vorhanden) |
| Horizontale Linie   | &lt;hr&gt;                      | --- |
| Kommentar           | &lt;!-- Kommentar --&gt;        | Nicht nativ |

---

# 7. Semantische HTML‑Tags

| HTML‑Tag (exakt)                     | Bedeutung        | Markdown‑Alternative |
|--------------------------------------|------------------|-----------------------|
| &lt;header&gt;...&lt;/header&gt;     | Kopfbereich      | Keine |
| &lt;footer&gt;...&lt;/footer&gt;     | Fußbereich       | Keine |
| &lt;section&gt;...&lt;/section&gt;   | Abschnitt        | Keine |
| &lt;article&gt;...&lt;/article&gt;   | Inhaltseinheit   | Keine |
| &lt;nav&gt;...&lt;/nav&gt;           | Navigation       | Keine |
| &lt;main&gt;...&lt;/main&gt;         | Hauptinhalt      | Keine |
| &lt;aside&gt;...&lt;/aside&gt;       | Seiteninhalt     | Keine |

---

# 8. Formulare (nur HTML)

Markdown unterstützt keine Formulare.

| Element        | HTML‑Code (exakt) |
|----------------|-------------------|
| Formular       | &lt;form action="/send" method="post"&gt;...&lt;/form&gt; |
| Textfeld       | &lt;input type="text" name="name"&gt; |
| Passwortfeld   | &lt;input type="password" name="pwd"&gt; |
| Checkbox       | &lt;input type="checkbox" checked&gt; |
| Radiobutton    | &lt;input type="radio" name="x"&gt; |
| Button         | &lt;button&gt;Klick&lt;/button&gt; |
| Dropdown       | &lt;select&gt;&lt;option&gt;A&lt;/option&gt;&lt;/select&gt; |

---

# 9. GitHub‑Flavored Markdown (GFM)

| Funktion                | HTML‑Code (exakt) | Markdown‑Code |
|-------------------------|-------------------|----------------|
| Aufgabenliste           | —                 | - [ ] offen<br>- [x] fertig |
| Tabellen erweitert      | —                 | GFM‑Tabellen |
| Inline‑HTML             | Wird gerendert    | Text |
| Codezeilen hervorheben  | —                 | ```js<br>console.log("Hi")<br>``` |

---

# 10. Kompaktes Cheat‑Sheet

## Markdown kurz & knapp

