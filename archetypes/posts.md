---
date = '{{ time.Now.Format "2006-01-02" }}'
draft = false
title = '{{ replace .File.ContentBaseName `-` ` ` | title }}'
[params]
  author = 'Qingsheng Fu'
---

**Insert Lead paragraph here.**
