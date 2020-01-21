# JavaScript Handout

Kommentare werden mit zwei Schrägstrichen gekennzeichnet und nicht vom Browser ausgewertet:
```javascript
// Dies ist ein Kommentar
```

## Variablenzuweisung
```javascript
var nameMax = "Max Mustermann";

var alter;
alter = 25;
```

## Primitive Datentypen
```javascript
var length = 16; // Nummer
var lastName = "Johnson"; // String
var cars = ["VW", "Toyota", "Tesla", "Ford"]; // Array TODO: eigener Teil
var isItSaturday = true; // Boolean
```

## Konsolenausgabe
```javascript
// Ausgabe Wert direkt
console.log("Moin"); // Ausgabe: Moin

// Ausgabe Variable
var greeting = "Hello, Develop<HER>!";
console.log(greeting) // Ausgabe: Hello, Develop<HER>!

var year = 2020;
console.log(year) // Ausgabe: 2020
```

## Arithmetische Operationen
```javascript
// Addition
console.log(11 + 4); // Ausgabe: 15

var addition = 11 + 4;
console.log(addition); // Ausgabe: 15

// Subtraktion
var subtraktion = 11 - 4;
console.log(addition); // Ausgabe: 7

// Multiplikation
var multiplikation = 11 * 4;
console.log(addition); // Ausgabe: 44

// Division
var division = 11 / 4;
console.log(addition); // Ausgabe: 2.75
```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

## Objekt-Datentyp
```javascript
// Objekt-Definition
var beruf = {
    name: "Webentwicklerin", // Objekt-Eigenschaft
    arbeitgeber: "OTTO",
    wochenstunden: 37.5,
    gehalt: 4000
};

// Zugriff auf Objekt-Eigenschaften
console.log(beruf.name); // Ausgabe: Webentwicklerin
```

TODO: Hilfreiche Seiten (w3schools, MDN)