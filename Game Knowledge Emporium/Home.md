## Daily Lenses
___
```dataviewjs
function DailyLenses(lensType, numberToShow) {
	var notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.map(note => note.file);
		
	var displayNotes = .concat(notes
		.where(note => notes.indexOf(note) == 2));
	
	dv.header(3, `${lensType} Lenses: ***${displayNotes.name.join()}***`);

	displayNotes.forEach(note => dv.paragraph(`![[${note.path}#A Lens in the Book of lenses that asks the designer to consider ]]`));
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
