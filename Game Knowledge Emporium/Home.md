## Daily Lenses
___
```dataviewjs
function DailyLenses(lensType, numberToShow) {
	var notes = dv.pages(`#GameDesign/Lenses/${lensType}`)
		.sort()
		.map(note => note.file);
		
	var displayNotes = notes
		.where(note => CountNotes(notes, note, numberToShow));
	
	dv.header(3, `${lensType} Lenses: ***${displayNotes.name.join()}***`);

	for (const note of displayNotes) {
		dv.span(`![[${note.path}#A Lens in the Book of lenses that asks the designer to consider|clean no-h4 ]]`);
	}
}

function DayHash() {
	var today = new Date();
	
	var day = String(today.getDate()).padStart(2, '0');
	var month = String(today.getMonth() + 1).padStart(2, '0');
	var year = today.getFullYear();

	return year + (month * 3) + day;
}

function CountNotes(notes, note, numberToShow) {
	for(i = 0; i < numberToShow; i++) {
		if (notes.indexOf(note) == ((DayHash() + (i * 3)) % notes.length)) {
			return true;
		}
	}
	return false;
}

DailyLenses("Designer", 1);
DailyLenses("Player", 1);
DailyLenses("Experience", 1);
DailyLenses("Process", 1);
DailyLenses("Game", 1);
```
