---
layout: ../layouts/PageLayout.astro
title: "歌单"
description: "我喜欢的音乐"
---

这里可以放你喜欢的音乐歌单。

使用 `{% media audio %}` 标签嵌入网易云音乐或 QQ 音乐歌单：

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
    - https://music.163.com/#/playlist?id=17981074620
{% endmedia %}
