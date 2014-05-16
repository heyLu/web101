# Einführung

## Was ist "das Web"?

* Webseiten
    - haben eine Adresse (URL)
    - werden vom Browser heruntergeladen & angezeigt
    - eigentlich nur Text (HTML-Code)

        ```
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

                <p>Und das wichtigste: Links sehen <a href="a_link">so aus!</a></p>
            </body>
        </html>
    - befinden sich (meistens) auf einem Server (man kann sie aber auch
      lokal entwickeln und speichern, dann kann sie nur ebend niemand
      anders sehen)
* Client/Server
    - Browser sind Clients (Screen Reader, Suchmaschinen und andere
      Programme aber auch)
    - Server stellen die Webseiten bereit, d.h. sie bekommen Anfragen
      für bestimmte Adressen (URLs) und beantworten diese mit dem
      Quellcode
    - Clients folgen dann Verweisen (Links) in diesen Dokumenten und
      binden verschiedene Medien ein (CSS-Styles, JavaScript-Code,
      Bilder, Videos, Musik)
* Standards (HTML, CSS und JavaScript)
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

...
