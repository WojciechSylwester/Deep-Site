---
date modified: 2024-11-20 14:35
date created: 2024-11-20 12:20
tags: 
---
Created:  `= this.file.ctime`
Updated: `= this.file.mtime`
`= this.date-created`
`= this.date-modified`

`= this.date-created`
`= this.date-modified`

# Untitled 1

#tag1,
#tag2 ,


%% DATAVIEW_PUBLISHER: start
```dataview
list from #tag1 
```
%%

- [[content/Untitled 1.md|Untitled 1]]

%% DATAVIEW_PUBLISHER: end %%



tag2


%% DATAVIEW_PUBLISHER: start
```dataview
list from #tag2 
```
%%

- [[content/Untitled 2.md|Untitled 2]]
- [[content/Untitled 1.md|Untitled 1]]

%% DATAVIEW_PUBLISHER: end %%








```dataview
table file.ctime as "Created Time"
where file.path = this.file.path
```

```dataview
list file.ctime 
where file.path = this.file.path
```

```dataview
table file.ctime as "Created Time"
from ""
where file.path = this.file.path

```

```dataview
table file.ctime as "Created Time"
where file.path = this.file.path
```

```dataview
list WITHOUT ID file.ctime
where file.path = this.file.path

```








