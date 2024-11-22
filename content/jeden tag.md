---
date modified: 2024-11-22 20:39
date created: 2024-11-20 12:20
tags:
  - wydajność
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
| 2024-11-20 12:20 | 2024-11-20 15:30 |

%% DATAVIEW_PUBLISHER: end %%

----

