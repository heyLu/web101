---
title: Einführung
layout: page
---

# Einführung

## Ziele

* Grundlagen der Erstellung und Gestaltung von Webseiten
* Verständnis der Grundprinzipien des Webs
* Erstellung einer vollständigen Webseite
* Wissen wie und wo man mehr zu den Themen Lernen kann
* Überblick über die Grenzen und Möglichkeiten

## Was ist "das Web"?

###  Webseiten

- haben eine Adresse (URL)
- werden vom Browser heruntergeladen & angezeigt
- eigentlich nur Text (HTML-Code)
        
        <!doctype html>
        <html>
            <head>
                <title>Hallo, Web!</title>
                <meta charset="utf-8" />
            </head>

            <body>
                <h1>Hallo, Web!</h2>

                <p>Webseiten bestehen eigentlich bloß aus Text wie diesem hier.</p>

                <p>Man kann sich diesen Text auch von jeder Webseite anschauen.</p>

                <p>Und das wichtigste: Links sehen <a href="../introduction.html">so aus!</a></p>
            </body>
        </html>

    [(Beispiel anschauen)](examples/01-structure.html)
- befinden sich (meistens) auf einem Server (man kann sie aber auch
  lokal entwickeln und speichern, dann kann sie nur eben niemand
  anders sehen)

### Client/Server

- Browser sind Clients (Screen Reader, Suchmaschinen und andere
  Programme aber auch)
- Server stellen die Webseiten bereit, d.h. sie bekommen Anfragen
  für bestimmte Adressen (URLs) und beantworten diese mit dem
  Quellcode
- Clients folgen dann Verweisen (Links) in diesen Dokumenten und
  binden verschiedene Medien ein (CSS-Styles, JavaScript-Code,
  Bilder, Videos, Musik)

### Standards (HTML, CSS und JavaScript)

- die "Sprache" in der der Quellcode von Webseiten geschrieben sind
  heißt HTML
- wird von einem Konsortium definiert
- Browser setzen diese Definition dann um
- HTML beschreibt den Inhalt und die Struktur der Webseiten
- CSS beschreibt das Aussehen
- JavaScript ist die Programmiersprache die verwendet wird um
  dynamisches Verhalten zu realisieren (fast alle Seiten verwenden
  in irgendeiner Art JavaScript)

## Die erste Webseite

Erster Versuch: nur Text

- eigener oder [generierter Text](http://loripsum.net/api/5/plaintext)
- Datei `webseite.html` erstellen und den Text dort hinein kopieren
    * dazu brauchen wir einen Texteditor (Text ≠ Dokument)
- im Browser anschauen [(Beispiel)](examples/00-justtext.html)

Da fehlt irgendwie noch etwas ...

### HTML: (**H**yper**T**ext **M**arkup **L**anguage)

- besteht aus *Elementen* die mithilfe von *Tags* ausgezeichnet werden
    (damit der Browser weiß was gemeint ist)
- Beispiel

        <p>Das ist ein Absatz.
        HTML ignoriert Zeilenumbrüche, wenn wir also Zeilenumbrüche haben
        wollen müssen neue Absätze erzeugen</p>

        <p>Wir können ein bisschen schummeln indem wir das `br`-Element
        verwenden. Zum Beispiel so:
        <br />
        Allerdings ist das nicht besonders guter Stil, d.h. meistens
        verwendet man einfach mehrere Absätze.</p>

    [(Beispiel anschauen)](examples/02-paragraphs.html)
- Tags haben also einen Anfang und ein Ende, dazwischen steht der normale
    Text
    * Anfang: `<p>` (öffnendes Tag)
    * Ende: `</p>` (schließendes Tag)
- andere Tags:
    * `h1`, `h2`, `h3`, `h4`, `h5` und `h6`: Überschriften
    * `em`: "Betonung", wird meist kursiv angezeigt
    * `strong`: stärkere Betonung, wird meist fett angezeigt
- ausprobieren!

Das sieht noch nicht besonders schön aus, dafür gibt es CSS:

### CSS (Cascading Style Sheets)

- für den Anfang kopiert einfach das folgende HTML an den Anfang eurer Datei

        <style>
        body {
            margin: 0 auto;   /* zentriert den Text */
            max-width: 800px; /* legt die maximale Breite des Textes fest */
        }
        </style>
- Beispiele:
    * `color` (Schriftfarbe)
    * `background-color` (Hintergrundfarbe)
    * `font-size` (Schriftgröße) und `font-family` (Schriftart)
- Syntax: *Selektor* und dazugehörige *Regeln*
    * d.h. CSS-Anweisungen betreffen immer bestimmte HTML Elemente
    * Beispiel

            body {
                color: red;
            }

            a {
                color: green;
            }

        D.h. der Text innerhalb des `body`-Elementes wird rot angezeigt
        und der Text von Links wird grün angezeigt.

        [(Beispiel anschauen)](examples/03-colors.html)
- mit CSS lässt sich am besten "live" experimentieren, dafür gibt es die
    "Developer Tools" des Browsers (`Ctrl-Shift-I`)
