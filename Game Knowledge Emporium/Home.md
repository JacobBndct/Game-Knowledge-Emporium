```dataview
const numberToShow = 3
const notes = dv.pages('#PermanentNote')
	.sort(() => 0.5 - Math.random())
	.slice(0, numberToShow)
	.map(note => note.file.link);
dv.list(notes)

```
