# Cookiebar Modul

Das Modul beinhaltet ein vordefiniertes Set an CSS-Anweisungen für die Cookiebar-Erweiterung [contao-cookiebar von Codefog][1].

## Installation

Zuerst muss die Erweiterung per composer installiert werden:  
`composer require codefog/contao-cookiebar`

Anschließend kann die Datei `_cookiebar.scss` in den Themes-Ordner kopiert und über die globale SCSS-Datei (z. B. app.scss oder bootstrap.scss) eingebunden werden.

## Notwendige Anpassungen

In der Datei `__cookiebar.scss` sollten einige Werte an das Theme angepasst werden. Diese sind teilweise als TODO ausgezeichnet. Die TODO-Kommentare können nach der Fertigstellung entfernt werden.

### $cookiebar-width

Die Variable definiert die maximale Breite der Cookiebar auf großen Bildschirmen. Der voreingestellte Wert eigenet sich für einen Standard-Text, kann aber je nach Bedarf angepasst werden. Er beeinflusst neben der Breite der Cookiebar den ersten Breakpoint.

### background-color
Die Hintergrundfarbe der Cookiebar sollte zu einer im Theme definierten Farbvariable geändert werden.

### .cookiebar__link
Der Link für weitere Informationen erbt die Styles von Elternelementen. Sollten im Theme noch keine Definitionen für Links und deren Farbe in verschiedenen Zuständen (:hover, :active) definiert worden sein, müssen diese hier eingetragen werden.

[1]: https://packagist.org/packages/codefog/contao-cookiebar
