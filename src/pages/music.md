---
layout: ../layouts/PageLayout.astro
title: "歌单"
description: "我喜欢的音乐"
---




```markdown
{% media audio %}
- title: 我的歌单
  list:
    - https://music.163.com/#/playlist?id=你的歌单ID
{% endmedia %}
```

{% media audio %}
- title: 悲哀收藏夹
  list:
    - https://music.163.com/#/playlist?id=6990784696
- title: 许嵩
  list:
    - https://music.163.com/#/album?id=16953
{% endmedia %}
