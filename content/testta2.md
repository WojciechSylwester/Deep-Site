---
date modified: 2024-11-20 15:30
date created: 2024-11-20 12:20
tags:
  - "#ta1"
---
%% DATAVIEW_PUBLISHER: start
```dataview
table without id file.ctime as "Created",
file.mtime as "Updated"
where file.path = this.file.path
```
%%

| Created          | Updated          |
| ---------------- | ---------------- |
| 2024-11-20 15:40 | 2024-11-20 15:40 |

%% DATAVIEW_PUBLISHER: end %%

----
b
