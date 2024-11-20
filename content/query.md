---
date modified: 2024-11-20 16:03
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




%% DATAVIEW_PUBLISHER: start
```dataview
list from #tag1 
```
%%



%% DATAVIEW_PUBLISHER: end %%



tag2


%% DATAVIEW_PUBLISHER: start
```dataview
list from #tag2 
```
%%



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









%% DATAVIEW_PUBLISHER: start
```dataview
list WITHOUT ID dateformat(file.ctime, "yyyy-MM-dd HH:mm" )
where file.path = this.file.path
```
%%

- 2024-11-20 15:40

%% DATAVIEW_PUBLISHER: end %%




%% DATAVIEW_PUBLISHER: start
```dataview
table without id tags
from "content"
where file.name != this.file.name
flatten file.tags as tags
group by tags
```
%%

| tags       |
| ---------- |
| #DMatrix   |
| #jupyter   |
| #wydajność |
| #XGB       |

%% DATAVIEW_PUBLISHER: end %%

%% DATAVIEW_PUBLISHER: end %%




%% DATAVIEW_PUBLISHER: start
```dataview
list WITHOUT ID dateformat(file.ctime, "yyyy-MM-dd HH:mm" )
where file.path = this.file.path
```
%%

- 2024-11-20 15:40

%% DATAVIEW_PUBLISHER: end %%