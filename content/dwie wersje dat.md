---
date modified: 2024-11-22 12:13
date created: 2024-11-20 12:20
tags: 
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
| 2024-11-22 12:05 | 2024-11-22 12:13 |

%% DATAVIEW_PUBLISHER: end %%

----

test



test



%% DATAVIEW_PUBLISHER: start
```dataview
table without id file.frontmatter["date created"] as "Created",
file.frontmatter["date modified"] as "Updated"
where file.path = this.file.path
```
%%

| Created          | Updated          |
| ---------------- | ---------------- |
| 2024-11-20 12:20 | 2024-11-22 12:13 |

%% DATAVIEW_PUBLISHER: end %%

sortowanie Explorer.tsx wg dat
```
  sortFn: (a: FileNode, b: FileNode) => {

    const dateA = a.file?.frontmatter?.["date modified"]

      ? new Date(a.file.frontmatter["date modified"])

      : new Date(0);

    const dateB = b.file?.frontmatter?.["date modified"]

      ? new Date(b.file.frontmatter["date modified"])

      : new Date(0);

    return dateB.getTime() - dateA.getTime(); // Sortuj według daty modyfikacji (najpierw najnowsze)

  },
```