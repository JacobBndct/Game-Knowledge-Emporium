```
<%*
const dv = app.plugins.plugins.dataview.api

const candidates = await dv.tryQuery(`
  LIST WITHOUT ID file.path
  FROM #daily_random_note
`)
const randomNo = Math.floor(Math.random() *
  (candidates.values.length - 1))
const filename = candidates.values[ randomNo ]
const randomContent = await dv.io.load(filename)  
_%>

... 

<% randomContent %>
```
