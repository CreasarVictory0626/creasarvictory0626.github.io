---
layout: ../layouts/PageLayout.astro
title: "歌单"
description: "我喜欢的音乐"
---

这里可以放你喜欢的音乐歌单。

使用 `{% media audio %}` 标签嵌入网易云音乐或 QQ 音乐歌单：

<!-- ```markdown
{% media audio %}
- title: 许嵩
  list:
    - https://music.163.com/#/my/m/music/playlist?id=17981074620
{% endmedia %}
``` -->

{% media audio %}
- title: 许嵩
  list:
    - https://music.163.com/#/my/m/music/playlist?id=17981074620
- title: 我喜欢的歌单
  list:
    - https://music.163.com/#/my/m/music/playlist?id=875679570
{% endmedia %}
