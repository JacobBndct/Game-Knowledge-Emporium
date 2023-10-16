```dataviewjs
const numberToShow = 1
const notes = dv.pages("#GameDesign/Lenses")
	.sort(() => 0.5 - Math.random())
	.slice(0, numberToShow);
dv.list(dv.fileLink("Stops", true))
```
