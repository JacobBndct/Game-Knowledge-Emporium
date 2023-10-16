```dataviewjs
const numberToShow = 3
const notes = dv.pages('#Math')
	.sort(() => 0.5 - Math.random())
	.slice(0, numberToShow)
	.map(note => note.file.link);
dv.list(notes)

```
