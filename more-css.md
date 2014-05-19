---
title: Mehr CSS
layout: page
---

# Mehr CSS

HTML alleine ist ein bisschen langweilig, mit CSS wird es schöner. :)

Je nachdem was euch interessiert können wir mit folgenden Dingen weitermachen:

* Wie setzt man Design-Ideen mit CSS um?
* schönere Navigation zwischen Seiten
* "sticky" Elemente (scrollen nicht mit)
* verschiedene Stile von Seiten
    - Blog
    - ein Tumblr-ähnlicher Blog
    - einzelne Artikel
* weitere Anwendungen:
    - Grids
    - Gallerien mit [Lightbox](http://www.lokeshdhakar.com/projects/lightbox2/)
* Wünsche?

# CSS Grundlagen

* die Elemente der Seite befinden sich in Rechtecken ("boxes")
* wichtige Eigenschaften:
    - `position`
    - `margin`, `padding`
    - `width`, `max-width`
    - `border`

# Wie setzt man Design-Ideen mit CSS um?

* Elemente können
    - fixiert werden (zB. eine Navigationsleiste ganz oben)
    - an einem Grid ausgerichtet werden
    - nicht mit scrollen
* Beispiel aussuchen (eins von den vorgeschlagenen oder eigene gewählte)
    und experimentieren
* Tips
    - immer mit Vorlagen/Inspirationen arbeiten (aber natürlich nicht genau
        kopieren und auf die Arbeit der anderen verweisen)
    - es ist völlig ok und hilfreich sich die Tricks anderer Seiten
        anzuschauen
    - vorher aufmalen hilft immer
    - mit Größen, Farben, Schriftarten etc. "live" experimentieren

# Navigation zwischen Seiten

* feste Leiste mit Navigationselementen am oberen Rand der Seite

[(Beispiel anschauen)](examples/header.html)

* alternativ: Navigationsleiste etwas weiter unterhalb, zB. nach
    einem Bild ("tumblry" Stil)

# Vorgefertigte Stile

* Blog, [(Beispiel anschauen)](examples/pretty-blog.html)
* Tumblry, [(Beispiel anschauen)](examples/tumblry.html)
* großer Artikel, [(Beispiel anschauen)](examples/article.html)

# Grids

* die Platzierung von Elementen nebeneinander ist etwas kompliziert ohne
    weitere Hilfen
* deswegen: Verwendung von Grids (werden schon lange für nicht-web Design
    verwendet)
* hier: [Gridism](http://cobyism.com/gridism)

<!-- ... -->

    <div class="grid">
        <div class="unit whole red"><pre>groß</pre></div>
    </div>

    <div class="grid">
        <div class="unit half green"><pre>halb</pre></div>
        <div class="unit half orange"><pre>und halb</pre></div>
    </div>

[(Beispiel anschauen)](examples/09-grid.html)

# Weiterführende Links

deutsch:

* [SelfHTML](http://wiki.selfhtml.org/wiki/Startseite)

englisch:

* [Learn CSS Layout](http://learnlayout.com/), erklärt die Grundlagen sehr
    gut in aufeinander aufbauenden Schritten
* [A Beginner's Guide to HTML & CSS](http://learn.shayhowe.com/html-css/)
* [An Advanced Guide to HTML & CSS](http://learn.shayhowe.com/advanced-html-css/)
* [HTML & CSS Kurs bei Codecademy](http://www.codecademy.com/tracks/web)
* [Übersicht zu CSS Properties][mdn-css-reference]
* [CSS Diner- Where we feast on CSS Selectors](http://flukeout.github.io),
    ein Spiel zum Verständnis von CSS Selektoren

## Tools

* [Gridism](http://cobyism.com/gridism), einfaches Grid Framework
* [Bootstrap](http://getbootstrap.com), populäres, sehr umfangreiches
    CSS Framework
* [Can I Use](http://caniuse.com), Übersicht für die Browser-Unterstützung
    von neueren CSS & HTML Elementen
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/icons/), viele
    Icons für Webseitendesign
* kommerziell:
    - [Webflow](https://webflow.com/), online Designer für Webseiten (nur in
        sehr kleinem Rahmen kostenfrei nutzbar, für kleine Projekte eventuell
        lohneswert wenigstens zum herumspielen)
    - [Macaw](http://macaw.co/), ebenfalls ein Design Programm für Webseiten,
        es gibt eine [Ausprobier-Version](http://download.macaw.co/)

[mdn-css-reference]: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

## Inspiration

* [A List Apart](http://alistapart.com)
* [clairelegrand.tumblr.com](http://clairelegrand.tumblr.com/post/77700679900/the-importance-of-the-unlikable-heroin)
* der Blog von [Danielle Sucher](http://www.daniellesucher.com/blog/)
* [Die Eskapistin](http://thatgirlthere.wordpress.com/)
* [Hacker School](http://hackerschool.com)
* [incisive.nu](http://incisive.nu/2014/thinking-about-mozilla/)
* [jacobian.org](www.jacobian.org/writing/)
* [Holstee Manifesto](http://holstee.com/pages/manifesto)
* [tomayko.com](http://tomayko.com/writings/adopt-an-open-source-process-constraints)
* [Wizard for Mac](http://wizardmac.com/)
* [Dash](http://kapeli.com/dash)

# Weiter geht es mit dem [Veröffentlichen](publishing.html)
