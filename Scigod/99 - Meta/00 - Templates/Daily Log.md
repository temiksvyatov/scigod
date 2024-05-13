---
date:
  - <% tp.date.now("DD/MM/YYYY HH:mm") %>
tags:
  - Daily/Log
cssclasses:
  - daily
  - image-borders
  - log
  - <% tp.date.now("dddd") %>
---
# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY") %>
---
### Journal
#### <% tp.file.cursor() %>