---
date modified: 2024-11-20 12:34
date created: 2024-11-19T15:31:33+01:00
---
# temp 6

[frontmatter]
  lastmod = ["lastmod", ":fileModTime"] # Używaj daty z metadanych pliku
  date = ["date", ":fileModTime"]       # Domyślnie data pliku


<p>Data utworzenia: {{ .Date | time.Format "2006-01-02 15:04" }}</p>
<p>Data ostatniej modyfikacji: {{ .Lastmod | time.Format "2006-01-02 15:04" }}</p>


<p>Utworzono: {{ .Date | time.Format "2006-01-02 15:04" }}</p>
<p>Ostatnia modyfikacja: {{ .Lastmod | time.Format "2006-01-02 15:04" }}</p>
