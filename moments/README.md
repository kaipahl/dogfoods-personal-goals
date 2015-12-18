# Moments

### Sammlung der Highlights des Tages


17.12.2015
---
Auf dem _#tkhh_ von @spielfeldrand und @nedfuller Dank für _allesaussersport_ bekommen. Passiert zu selten und tut der Motivation gut :-)


16.12.2015
---
Mittagessen mit Connie – sehr feine Penne mit gebratenen Rinderpsitzen im Nuestro.


15.12.2015
---
Mittagessen mit einem netten, ehemaligen Projektkollegen. Im Riads, einem Libanesen an der Musikhalle.


14.12.2015
---
8 Stunden Zeit genommen um in das Markup, CSS und den JS-Code von zeit.de einzusteigen. Tat gut mit derartiger Muße sich eine Website anzuschauen. Ich bin heute abend von den Eindrücken erschlagen und habe noch nicht einmal alle Themen angefasst.


13.12.2015
---
Frühmorgens durch die Gegend gefahren und ein Geburtstagsgeschenk vor die Tür gestellt.


12.12.2015
---
Das Schreiben eines _Bankendossiers_ um sich nach Konditionen für einen Hypothekenkredit zu informieren, eskalierte im Aufwand, u.a. weil ich erst mal die Zahlen für meinen Lebensunterhalt der letzten Jahre errechnen musste – keine leichte Aufgabe für einen Selbstständigen, der alles über ein Konto laufen lässt. Am Ende bin ich happy, dass ich das Dossier geschrieben habe. Nun lasse ich es eine Woche lang liegen, um es nächstes Wochenende noch einmal durchzulesen.


11.12.2015
---
Ausnahmsweise das Highlight heute mal am darauffolgenden Morgen geschrieben. Es war ein eher highlightloser Tag. Ich könnte jetzt den elsäßischen Flammkuchen im Café Nuestro als Highlight benennen oder die Überlegungen zu meinem _Mission Statement_. Letzteres ist noch nicht abgeschlossen, aber gut gestartet. Es zeichnet sich ab, dass das _Mission Statement_ und meine Profilseite noch einige Tage brauchen werden, weil man sie öfters sacken lassen sollte um dann wieder drauf zu schauen.

10.12.2015
---
__Kunden-Website übergeben__ und __Projekt abgeschlossen__. Der Umzug der Website auf den Live-Server gestaltete sich leider etwas schwieriger – es handelte sich um eine Portfoliowebsite einer Grafikerin. Das CMS _ProcessWire_ bietet zwar für einen solchen Umzug die Möglichkeit eines „_Site Profile Exports_“ – nur dass der aus mir nicht bekannten Gründen nicht funktionierte. Es wurde zwar ein Export-Verzeichnis auf dem Testserver generiert, _ProcessWire_ erkannte aber bei der Installation auf dem Liveserver das Profil nicht. Also musste ich händisch Dateien und MySQL-Tabellen kopieren… Hat mich eine Stunde mehr gekostet als erwartet, aber am Ende war ich happy, dass das Projekt abgeschlossen werden konnte.


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
