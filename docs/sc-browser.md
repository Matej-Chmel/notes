# Nesouhlas s uchováním cookies

Tento skript zajistí, že uživatel vyjádří nesouhlas s *oprávněnými zájmy*.
Spusťte po kliknutí na tlačítko *Manage options*.

```js
document.querySelectorAll(
    ".fc-legitimate-interest-preference-container .fc-slider-el"
).forEach(e => e.click());
```
