---
created: 2024-11-18T14:52
updated: 2024-11-18T15:20
date modified: 2024-11-20 12:25
date created: 2024-11-18 14:52
---
# Temp 4
Created:  `= this.file.ctime`
Updated: `= this.file.mtime`

Created:  `$= this.file.ctime`
Updated: `$= this.file.mtime`

<%+ tp.file.creation_date("YYYY-MM-DD HH:mm") %>
date updated: <%+ tp.file.last_modified_date("YYYY-MM-DD HH:mm:ss") %>

<% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
<% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>

