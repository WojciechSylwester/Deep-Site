---
date modified: 2024-11-20 15:31
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
| 2024-11-20 15:30 | 2024-11-20 15:33 |

%% DATAVIEW_PUBLISHER: end %%

----

### Juputer Nootebook vs Jupyter Lab

Wydajność w nootebook jest większa niż w lab. 
Lab ma lepszą nawigacje.