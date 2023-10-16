```dataviewjs
function DailyLenses(lensType, numberToShow) {
	const notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.sort(() => 0.5 - Math.random())
		.slice(0, numberToShow)
		.map(note => note.file.path);
	
	dv.header(3, `${lensType} Lenses`);
	notes.forEach(note => dv.paragraph(`![[${note}#***A Lens in the Book of lenses that asks the designer to consider ***]]`));
}

DailyLenses("poop", 3);
DailyLenses("Game", 2);
```
