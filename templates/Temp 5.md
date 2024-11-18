---
created: 2024-11-18T15:07
updated: 2024-11-18T15:10
---

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



Created: <% = this.file.ctime %>
Updated: <% = this.file.mtime %>



Created: <%  this.file.ctime %>
Updated: <%  this.file.mtime %>


<% tp.file.creation_date("YYYY-MM-DD HH:mm") %>
<% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>