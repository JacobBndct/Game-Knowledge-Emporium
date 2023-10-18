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

function getRandomInt(min, max) {
    return min + ((17317 * DayHash()) % (max - min));
}

function randomInts(n, min, max, minSum, maxSum) {
    if (min * n > maxSum || max * n < minSum) {
       throw 'Impossible';
    }

    var ints = [];
    while (n--) {
        // calculate a lower bound for this number
        // n * max is the max of the next n numbers
        var thisMin = Math.max(min, minSum - n * max);
        // calculate an upper bound for this number
        // n * min is the min of the next n numbers
        var thisMax = Math.min(max, maxSum - n * min);

        var int = getRandomInt(thisMin, thisMax);
        minSum -= int;
        maxSum -= int;
        ints.push(int);
    }
    return ints; 
}

DailyLenses("Designer", 1);
DailyLenses("Player", 1);
DailyLenses("Experience", 1);
DailyLenses("Process", 1);
DailyLenses("Game", 1);
```
