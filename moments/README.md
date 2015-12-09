# Moments

### Sammlung der Highlights des Tages

09.12.2015
---
Zweimal mein Static Site Generator ___tug___. Ich habe _tug_ vor einigen Tagen intern auf eine Kundenwebsite angewendet, wo es [_Assemble_](http://assemble.io) abgelöst hat. Ich bin erst heute dazu gekommen, die generierten Seite per _diff_ mit den von _Assemble_ generierten Seiten zu vergleichen. Das _diff_ hat gezeigt, das es nur Unterschiede in den Whitespaces gab, aber ansonsten keine relevanten Code-Unterschiede. Damit kann _tug_ bei mir überall _Assemble_ ablösen, was so bei drei bis vier Sites der Fall sein dürfte.

Ich habe heute Nachmittag noch ein neues Feature für _tug_ implementiert. Im YAML Frontmatter jeder Page kann man nun ggf. das Attribut `publish: false` eintragen. Dann wird daraus _keine_ HTML-Seite generiert und keine Metadaten wie z.B. Tags in die site-weiten Daten übertragen. Kurz: die Seite existiert nur als Source, taucht aber nirgends produktiv auf. Zu meiner Freude ging das überraschend fix.

Bonus-Highlight: Eigentlich wollte ich das „_Professionell Entwickeln mit Javascript_“-Buch weiter lesen. Nicht zuletzt aufgrund von _tug_ beschäftigt mich aber aktuell das Thema „Funktionen“ in Javascript, so dass ich stattdessen alles an Büchern und eBooks durchnehme und dort jeweils die Kapitel zum Thema `function()` lese. Das zieht eine komplett andere Art des Fundaments ins Hirn ein, von Themen die man glaubte, das man sie irgendwei kennen würde…


08.12.2015
---
Großartige [Ausstellung im Hamburger Museum für Kunst und Gewerbe zu „__Jugendstil__“](http://www.mkg-hamburg.de/de/ausstellungen/aktuell/jugendstil-die-grosse-utopie.html) besucht. Die Ausstellung hat für mich erstmals eine Linie gezogen vom __Jugendstil__ über __Neoklassizismus__ zu __Art Déco__. Faszinierend war der nahtlose, räumliche Übergang in die bestehenden Räume zu Bauhaus und Moderne bzw. von den Jugendstil-Plakaten zu „Reklame-Plakate“. 

Ich hätte gerne noch mehr erfahren, wie die Grundidee des Jugendstils z.B. in der „Arts & Craft“-Bewegung (Widerstand gegen Industrialisierung, Demokratisierung durch Besinnung auf den Menschen) zwei bis drei Jahrzehnten später in unterschiedliche Richtungen auseinandergedriftet ist – in Neoklassizismus und Bauhaus, für die die Industrialisierung aufgrund der niedrigen Herstellungspreise zur Demokratisierung dazu gehörte oder Art Déco, der Luxusgüter als Schrittmacher für Kunst ansah.

07.12.2015
---
Bug auf Kundenwebsite gefixt, der auf ein seit mind. fünf Jahren existierenden Browser-Bug basiert, von dem die Browser-Hersteller anscheinend sich weigern ,ihn als Bug anzuerkennen: bekommt eine Website längeren Inhalt und erscheint dadurch eine vertikale Scrollbar, wird zwar der Viewport verkleinert. Trotzdem senden die Browser kein `resize`-Event. [Argumentation bei Mozilla](https://bugzilla.mozilla.org/show_bug.cgi?id=592221): Wieso `resize`? Das Fenster wird ja nicht kleiner, nur der Viewport – was wohl kaum konform mit den Erwartungen von Frontendlern ist.
