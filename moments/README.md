# Moments

### Sammlung der Highlights des Tages

07.12.2015
---
Bug auf Kundenwebsite gefixt, der auf ein seit mind. fünf Jahren existierenden Browser-Bug basiert, von dem die Browser-Hersteller anscheinend sich weigern ,ihn als Bug anzuerkennen: bekommt eine Website längeren Inhalt und erscheint dadurch eine vertikale Scrollbar, wird zwar der Viewport verkleinert. Trotzdem senden die Browser kein `resize`-Event. [Argumentation bei Mozilla](https://bugzilla.mozilla.org/show_bug.cgi?id=592221): Wieso `resize`? Das Fenster wird ja nicht kleiner, nur der Viewport – was wohl kaum konform mit den Erwartungen von Frontendlern ist.
