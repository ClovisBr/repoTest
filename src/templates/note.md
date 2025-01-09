---
uuid: <% tp.user.uuid() %>
tags: 🧠
status: BUILD
---
#### Links
<% await tp.file.move("2 - Building/notes/" + tp.file.title) %>

---
# <% tp.file.title %>
[[2 - Building/todo/todo - <% tp.file.title %>|✅]]
<% tp.file.cursor() %>