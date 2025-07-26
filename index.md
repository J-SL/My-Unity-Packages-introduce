---
layout: home
title: "欢迎来到我的 Unity 插件展示"
---

# 🎮 欢迎来到我的 Unity 插件展示

这里是我开发的 Unity 插件列表，你可以点击插件名称查看更多详情：

<div style="margin-top: 2em;">
  {% for plugin in site.data.plugins %}
    <div style="padding: 1em; border: 1px solid #ccc; border-radius: 8px; margin-bottom: 1em; background-color: #f9f9f9;">
      <h2 style="margin: 0 0 0.5em 0;">
        <a href="{{ plugin.url }}" style="text-decoration: none; color: #007acc;">🔗 {{ plugin.name }}</a>
      </h2>
      <p style="margin: 0;">{{ plugin.short_desc }}</p>
    </div>
  {% endfor %}
</div>

