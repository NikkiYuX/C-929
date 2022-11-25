---
{"dg-publish":true,"dg-permalink":"/<% tp.file.title %>","permalink":"/<% tp.file.title %>/"}
---

# <% tp.file.title %>

## Linked Mentions


---

```expander
/.*\[\[<% tp.file.title %>\]\].*(?:\r?\n(?!\r?\n).*)*/
## [[$filename]]
$match
```

<-->