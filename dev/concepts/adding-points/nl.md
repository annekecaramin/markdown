---
title: Punten toevoegen
order: 260
---

Nadat je [shorthand](/concepts/shorthand) gebruikt hebt, heeft `Point` de constructor voor nieuwe punten, en `points` is een referentie naar `part.points`, waar je je nieuwe punten moet opslaan.

Things will now *just work* when you do this:

```js
points.middenAchter  = new Point(0,0);
```

<Tip>

De [Point API docs](/api/point) heeft vele methoden om punten te maken.

</Tip>