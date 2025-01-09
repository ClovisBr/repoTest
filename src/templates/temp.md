---
status: TEMP
---
<% tp.file.cursor() %>
<% await tp.file.move("1 - Temporary/notes/" + tp.file.title) %>