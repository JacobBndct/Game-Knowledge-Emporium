### Daily Lenses
```dataviewjs
const numberToShow = 1
const notes = dv.pages('#GameDesign/Lenses')
	.sort(() => 0.5 - Math.random())
	.slice(0, numberToShow)
	.map(note => note.file.path);

dv.header(2, "Header");
notes.forEach(note => dv.paragraph(`![[${note}#***A Lens in the Book of lenses that asks the designer to consider ***]]`));
```
