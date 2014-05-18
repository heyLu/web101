---
title: Mehr HTML
layout: page
---

# Mehr HTML

Text alleine ist vielleicht ein bisschen langweilig. Aber HTML kann viel
mehr...

## Bilder

* Bilder werden mit dem `img`-Element ausgezeichnet

        <h1>Eine Katze!</h1>
        
        <img src="http://placekitten.com/400/400?image=9" />

    [(Beispiel anschauen)](examples/04-images.html)
* etwas komplizieres HTML
    - selbstschließende Elemente (`<... />`)
    - Attribute (`src="..."`)

## Listen

Manchmal möchte man Dinge aufzählen.

    <p>Niedliche Katzen</p>

    <ul>
        <li><img src="http://placekitten.com/300/300?image=1" /></li>
        <li><img src="http://placekitten.com/300/300?image=5" /></li>
        <li><img src="http://placekitten.com/300/300?image=12" /></li>
        <li>und viele mehr...</li>
    </ul>

    <p>Aller guten Dinge sind drei.</p>
    
    <ol>
        <li>Eins</li>
        <li>Zwei</li>
        <li>Drei</li>
    </ol>

[(Beispiel ansehen)](examples/05-lists.html)

## Tabellen

    <table>
        <thead>
        <tr>
            <td>Name</td>
            <td>Alter</td>
            <td>Beschreibung</td>
        </tr>
        </thead>

        <tbody>
        <tr>
            <td>Fred</td>
            <td>7</td>
            <td>abenteuerlustig, Äpfel sind toll</td>
        </tr>
        <tr>
            <td>Paula</td>
            <td>11</td>
            <td>mag (richtige) Mathematik</td>
        </tr>
        </tbody>
    </table>

[(Beispiel ansehen)](examples/06-tables.html)

## Videos

* eigentlich `<video src="wonderful-world.mp4" />`
* allerdings ist es etwas komplizierter
    - dafür muss man die URLs der Videodateien kennen
    - YouTube, Vimeo & Co erlauben das aber nicht (wirklich)
* deswegen: "embed" Codes
    - HTML Code den man von YouTube bekommt und auf seiner Seite
        verwendet um das Video "einzubetten"
    - dafür geht man auf die Seite des Videos, zB. <https://www.youtube.com/watch?v=QncgmzH6yQU>,
        klickt auf "Share", dann auf "Embed" und kopiert den Code
        dort auf die eigene Seite

<!-- ... -->

    <iframe width="560" height="315"
        src="//www.youtube.com/embed/QncgmzH6yQU"
        frameborder="0" allowfullscreen>
    </iframe>

[(Beispiel ansehen)](examples/07-videos.html)

(Das könnte ihr zB. auch mal mit Videos von Vimeo ausprobieren: <https://vimeo.com/15311681>)

## Audio

Funktioniert ähnlich wie bei Videos. Auch ausprobieren: <https://soundcloud.com/mio_myo/sternwarte-observatory-ep-01>

## Noch viel mehr Elemente

* die am häufigsten benutzten Elemente kennen wir jetzt
* gibt es noch welche die ihr gerne verwenden wollt?
* es gibt aber noch mehr, hier ist [eine Übersicht][html-elements]
    (auf englisch)

[html-elements]: http://www.w3.org/TR/html-markup/elements.html

## Mehrere Seiten

* bisher nur Links zu *anderen* Seiten
* mehrere Seiten brauchen Links *untereinander*

<!-- ... -->

Eine Seite:

    <!-- 08-links1.html -->
    
    <p>Link zur <a href="08-links2.html">anderen Seite</a>.</p>

    <p>Oder wieder <a href="../more-html.html">zurück zum Workshop</a>.</p>

Und eine andere:

    <!-- 08-links2.html -->

    <p>Und wieder <a href="08-links1.html">zurück</a>.</p>

[(Beispiel anschauen)](examples/08-links1.html)

Obwohl das vielleicht ziemlich einfach klingt kann man damit alleine schon
"choose-your-own-adventure" Geschichten bauen. Und natürlich verwendet man
Links zwischen den eigenen Seiten auf fast jeder Webseite.

## Weitergehende Links

* [Twine](http://twinery.org/), interaktive, nicht-lineare Geschichten
    (eine fortgeschrittene Variante der Verwendung von Links um Geschichten
     zu erzählen)
* [Übersicht über HTML Elemente][html-elements] (englisch)
* alternativ eine [andere Übersicht][mdn-elements] mit mehr Erklärungen und
    Beispielen (es gibt auch eine unvollständige
    [deutsche Version][mdn-elements-de])

[mdn-elements]: https://developer.mozilla.org/en/docs/Web/HTML/Element
[mdn-elements-de]: https://developer.mozilla.org/de/docs/Web/HTML/Element

## Weiter geht es mit [schöneren Webseiten](more-css.html)
