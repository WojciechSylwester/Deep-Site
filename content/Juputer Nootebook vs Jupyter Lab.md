---
date modified: 2024-11-20 23:28
date created: 2024-11-20 12:20
tags:
  - jupyter
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
| 2024-11-20 15:33 | 2024-11-20 15:35 |

%% DATAVIEW_PUBLISHER: end %%

----
Wydajność w nootebook jest większa niż w lab. 
Lab ma lepszą nawigacje.