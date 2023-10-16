## Daily Lenses
___
```dataviewjs
function DailyLenses(lensType, numberToShow) {
	const notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.where(note => (DayHash() % notes.length) <= note.index <= ((DayHash() + numberToShow) % notes.length)) 
		.map(note => note.file);

	dv.header(3, `${lensType} Lenses: ${notes.name.join()}`);

	notes.forEach(note => dv.paragraph(`![[${note}#A Lens in the Book of lenses that asks the designer to consider ]]`));
}

function DayHash() {
	var today = new Date();
	
	var day = String(today.getDate()).padStart(2, '0');
	var month = String(today.getMonth() + 1).padStart(2, '0');
	var year = today.getFullYear();

	return year + month * 3 + day * 7;
}

DailyLenses("Designer", 1);
DailyLenses("Player", 1);
DailyLenses("Experience", 1);
DailyLenses("Process", 1);
DailyLenses("Game", 1);
```
