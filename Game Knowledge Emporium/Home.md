## Daily Lenses
___
```dataviewjs
function DailyLenses(lensType, numberToShow) {
	const notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.map(note => note.file.path);
	dv.header(3, `${lensType} Lenses`);
	notes.forEach(note => dv.paragraph(`![[${note}#***A Lens in the Book of lenses that asks the designer to consider ***]]`));
}

function DayHash() {
	```javascript
var today = new Date();
var dd = String(today.getDate()).padStart(2, '0');
var mm = String(today.getMonth() + 1).padStart(2, '0'); //January is 0!
var yyyy = today.getFullYear();
```
}

DailyLenses("Game", 1);

```
