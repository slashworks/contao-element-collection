# Formular Modul

Das Modul beinhaltet ein vordefiniertes Set an CSS-Anweisungen für Standard Contao Formulare. Ebenso ist ein neues Formularfeld enthalten, das einen Zeilenumbruch im Formular ermöglicht (bei Verwendung von display: flex bestehen keine anderen guten Möglichkeiten).

## CSS

Die Datei `_form.scss` kann in das eigene Theme eingebunden werden und deckt die grundlegenden Formular-Elemente ab.  
In der Datei sind sollten einige Werte an das Theme angepasst werden. Diese sind als TODO gekennzeichnet. Ist die Bearbeitung abgeschlossen, können die TODO-Kommentare gelöscht werden.

## Templates

Für einige Formular-Elemente (z. B. select, radio buttons, checkbox) sind angepasste Templates enthalten, die in den templates-Ordner kopiert werden sollten. Für diese Elemente sind ebenso Icons vorgesehen, die über das simple-svg-icons-bundle eingebunden werden können.

## Formular-Element: LineBreak

Um in Formularen einen Zeilenumbruch zwischen zwei Widgets zu erzielen, kann ein neues Formularfeld vom Typ "Zeilenumbruch" ausgegeben werden. Das kann z. B. zwischen zwei Widgets eingesetzt werden, die jeweils nur 50% breit sind, aber untereinander stehen sollen.
