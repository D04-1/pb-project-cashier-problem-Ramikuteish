# The Cashier Problem Projekt

Es ist ein Programm, das einer Kassierer hilft, den Kunden angemessenes Wechselgeld (die Menge an Scheinen und Münzen) zu geben.

Ich habe den Code komplet mit JavaScript Sprache gebaut und auf der suche im Googel wie (MDN) seite und hilfe von anderen.

Mit (console.log) kann man immer testen ,ob die Schritte richtig sind, damit man weiter macht oder korrigiert.
Und im Terminal (node.lösung.js) ausgeben, um das Ergebnis zu sehen.

# Beispiel 1 :

Wenn der Preis 3,75 € beträgt und der bezahlte Betrag ( paid amount ) 50 €, dann sollte der Kunde 46,25 € Wechselgeld (receive) zurückbekommen.

```js
casher(50, 3.75);
- Die erwartete Ausgabe sollte sein:
- 2 x €20 // 2 twenty euro notes
- 1 x €5 // 1 five euro note
- 1 x €1 // 1 euro
- 1 x €0.2 // 1 twenty cent coin
- 1 x €0.05 // 1 five cent coin
```

# Beispiel 2 :

Wenn der Preis 4.5 € beträgt und der bezahlte Betrag ( paid amount ) 20 €, dann sollte der Kunde 15.5 € Wechselgeld (receive) zurückbekommen.

```js
casher(20, 4.5);
- Die erwartete Ausgabe sollte sein:
- 2 x €10 // 2 ten euro notes
- 1 x €5 // 1 five euro note
- 1 x €0.50 // 1 fifty cents coin
```

# Beispiel 3 :

Wenn der Preis 15 € beträgt und der bezahlte Betrag ( paid amount ) 10 €, dann reich es nicht Wechselgeld (receive) zurückzubekommen.

```js
casher(10, 15);
- Die erwartete Ausgabe sollte sein:
- that is not enough
```
