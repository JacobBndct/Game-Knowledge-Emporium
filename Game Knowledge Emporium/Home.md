## Daily Lenses
___
```dataviewjs
function DailyLenses(lensType, numberToShow) {
	const notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.map(note => note.file.path);
	dv.header(3, `${lensType} Lenses`);
	notes.forEach(note => dv.paragraph(`![[${note}#***A Lens in the Book of lenses that asks the designer to consider ***]]`));
}

DailyLenses("Game", 1);

```
