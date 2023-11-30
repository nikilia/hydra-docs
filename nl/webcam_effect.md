## Maak je eigen webcam effect

1. Voordat je de webcam als bron kunt gebruiken moet deze eerst worden geïnitialiseerd met behulp van `s0.initCam()`. Dit creëert een bron met de naam `s0` die aan de webcam wordt gekoppeld.
⋅
```javascript
s0.initCam()
```

2. Nu ga je de webcam weergeven door middel van de `src()` bron. Hierin selecteer je `s0` die in de vorige stap aan de webcam is gekoppeld.

3. Voeg ook `.out()` toe en controleer met *`ctrl+shift+enter`* of het werkt.
⋅
```javascript
s0.initCam()
src(s0)
.out()
```
⋅
⋅Kun je jezelf zien? Dan kunnen we verder met het beeld transformeren!

4. Gebruik de transformatie `.colorama(0.5)` om de kleuren te beïnvloeden. Speel met de waarden tussen de haakjes totdat je een leuk resultaat hebt.
⋅
```javascript
s0.initCam()
src(s0)
.colorama(0.1)
.out()
```

5. Voeg andere transformaties toe of gebruik een andere bron in plaats van de webcam. Probeer verschillende waarden en volgordes van transformaties. Hieronder een voorbeeld van gecombineerde transformaties.
⋅
```javascript
s0.initCam()
src(s0)
.colorama(0.85)
.pixelate(80,80)
.repeat(3,3)
.rotate(0.2,0.2)
.kaleid(4)
.out()
```
![alt text](images/voorbeeld2.jpg)

### Thuis verder gaan?
Scan de QR code met je telefoon om deze website op te slaan!

![alt text](images/QR.png)
