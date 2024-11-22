---
date modified: 2024-11-22 13:26
date created: 2024-11-20 12:20
tags:
  - wydajność
  - XGB
  - DMatrix
t1: 
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
| 2024-11-20 15:35 | 2024-11-20 15:36 |

%% DATAVIEW_PUBLISHER: end %%

----
Wydajność w XGB jest większa przy użyciu DMatrix.
