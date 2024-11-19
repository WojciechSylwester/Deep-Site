---
date modified: 2024-11-19T01:23:59+01:00
date created: 2024-11-19T01:17:23+01:00
link: "#tag1"
tags:
  - tag1
---
```dataview
TABLE WITHOUT ID Tag, map(rows, (r) => link(r.file.link, r.title)) AS Notes
FROM "content"
FLATTEN file.tags as Tag
GROUP BY Tag
WHERE !contains(file.path,this.file.path) AND econtains(this.file.tags, Tag)
```

```dataview
TABLE WITHOUT ID Tag, map(rows, (r) => link(r.file.tag, r.title)) AS Notes
FROM "content"
WHERE file.path != this.file.path
FLATTEN file.tags as Tag
GROUP BY Tag
WHERE econtains(this.file.tags, Tag)
```


#tag1 