```dataviewjs
const numberToShow = 1
const notes = dv.pages('#GameDesign/Lenses')
	.sort(() => 0.5 - Math.random())
	.slice(0, numberToShow)
	.map(note => dv.fileLink(note.file.path, true));
dv.list(notes)
```
