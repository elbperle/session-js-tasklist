# HTML-Handout

## Das HTML-Grundgerüst
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Titel</title>
  </head>
  <body>

  </body>
</html>
```
### HTML-Tags
|     HTML-Tag    |                                                               Bedeutung                                                              |
|:---------------:|:------------------------------------------------------------------------------------------------------------------------------------:|
|     `<head>`    |                                                Beinhaltet Informationen über die Seite                                               |
|    `<title>`    |                                        Definiert u. a. den Text, welcher im Tab angezeigt wird                                       |
|     `<body>`    |                                  Enthält die eigentlichen, vom Browser darzustellenden Informationen                                 |
| `<h1>`...`<h6>` | Definiert eine Überschrift.<br> `<h1>` definiert die wichtigste Überschrift. `<h6>` definiert die am wenigsten wichtige Überschrift. |

## Ungeordnete HTML-Listen mit `<ul>` 
```html
<ul>
    <li>Banane</li>
    <li>Apfel</li>
    <li>Orange</li>
    <li>Kiwi</li>
</ul>
```
Darstellung im Browser:
<ul>
    <li>Banane</li>
    <li>Apfel</li>
    <li>Orange</li>
    <li>Kiwi</li>
</ul>

Mit `<li>` wird ein Listenelement definiert

## `<form>` Element
Definiert ein Formular, das zum Erfassen von Benutzereingaben verwendet wird:
```html
<form>
    <label for="myTextInputField">Text hier einfügen:</label>
    <input type="text" name="myTextInputField" placeholder="Text eingeben">
    <input type="submit" value="Senden">
</form>
```
Dies sieht wie folgt im Browser aus:

<form>
    <label for="myTextInputField">Text hier einfügen:</label>
    <input type="text" name="myTextInputField" placeholder="Text eingeben">
    <input type="submit" value="Senden">
</form>

* Durch das `<label for="myTextInputField">`-Tag wird eine Beschriftung für das Eingabefeld "myTextInputField" defniert
* Das `<input type="text" name="myTextInputField" placeholder="Text eingeben">`-Tag definiert das eigentliche Eingabefeld mit dem Namen "myTextInputField" und dem Platzhalter-Text
* Das `<input type="submit" value="Senden">`-Tag definiert den Senden-Button

## Einbindung von CSS und JavaScript in HTML
* Einbindung von CSS mit dem `<style>`-Tag
* Einbindung von JavaScript mit `<script>`-Tag

# Hilfreiche Seiten
* [w3schools](https://www.w3schools.com/)
* [MDN](https://developer.mozilla.org/de/)
* [selfhtml](https://wiki.selfhtml.org/)