```dataview
LIST FROM "100 Daily"
WHERE title.year = date(<% tp.file.title %>).year & title.month = date(<% tp.file.title %>).month
SORT title asc
```