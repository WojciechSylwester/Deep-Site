---
created: 2024-11-18T14:52
updated: 2024-11-18T15:20
date modified: 2024-11-19T15:38:23+01:00
date created: 2024-11-19T14:46:11+01:00
---
Created:  `= this.file.ctime`
Updated: `= this.file.mtime`

Created:  `$= this.file.ctime`
Updated: `$= this.file.mtime`

NaN
date updated: NaN

2024-11-19 14:46
2024-11-19 14:46

tat

<p>Data utworzenia: {{ page.date | date: "%Y-%m-%d %H:%M" }}</p>
<p>Data ostatniej modyfikacji: {{ page.last_modified_at | date: "%Y-%m-%d %H:%M" }}</p>


<p>Updated: `$= this.file.mtime` </p>

Updated: `||= this.file.mtime`

<p>Updated: `= this.file.mtime` </p>

<p> as`$= <% tp.file.creation_date("YYYY-MM-DD HH:mm") %> `  asd </p>


<p><% tp.file.last_modified_date("YYYY-MM-DD HH:mm") %>

<% tp.file.last_modified_date("YYYY-MM-DD HH:mm:ss") %> </p>


[frontmatter]
  lastmod = ["lastmod", ":fileModTime"] # Używaj daty z metadanych pliku
  date = ["date", ":fileModTime"]       # Domyślnie data pliku


<p>Data utworzenia: {{ .Date | time.Format "2006-01-02 15:04" }}</p>
<p>Data ostatniej modyfikacji: {{ .Lastmod | time.Format "2006-01-02 15:04" }}</p>


<p>Utworzono: {{ .Date | time.Format "2006-01-02 15:04" }}</p>
<p>Ostatnia modyfikacja: {{ .Lastmod | time.Format "2006-01-02 15:04" }}</p>
