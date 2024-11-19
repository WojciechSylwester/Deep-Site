---
created: 2024-11-18T14:52
updated: 2024-11-18T15:20
date modified: Tuesday, November 19th 2024, 2:36:59 pm
date created: Tuesday, November 19th 2024, 1:39:54 pm
---

Created:  `= this.file.ctime`
Updated: `= this.file.mtime`

Created:  `= this.file.ctime`
Updated: `= this.file.mtime`
NaN
date updated: NaN

2024-11-19 13:39
2024-11-19 13:39


jupyter notebook jest szybszy w wykonywaniu niż jupyter lab.


`$= dv.el('span', dv.current().file.ctime.toLocaleString(DateTime.DATETIME_SHORT))`


`$= dv.el('span', dv.current().file.mtime.toLocaleString(DateTime.DATETIME_SHORT))`

`$= dv.el('span', dv.current().file.mtime.toLocaleString())`

Created:  `= this.file.ctime.toString()`
