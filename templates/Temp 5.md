---
created: 2024-11-18T15:07
updated: 2024-11-18T15:19
date modified: 2024-11-20 12:34
date created: 2024-11-18 15:07
---
# Temp 5

Created:  = this.file.ctime
Updated: = this.file.mtime

Created:  '''= this.file.ctime'''
Updated: '''= this.file.mtime'''

Created:  '= this.file.ctime'
Updated: '= this.file.mtime'


Created:  ``= this.file.ctime``
Updated: ``= this.file.mtime``

Created: `= this.file.ctime`
Updated: `= this.file.mtime`



Created: <%+ = this.file.ctime %>
Updated: <%+ = this.file.mtime %>



Created: `<%+  this.file.ctime %>`
Updated: `<%+  this.file.mtime %>`


<% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
<% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>