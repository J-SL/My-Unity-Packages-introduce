---
layout: home
title: "🎮 欢迎来到我的 Unity 插件库"
---

<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }
  .plugin-list {
    list-style: none;
    padding-left: 0;
  }
  .plugin-list li {
    background: #f7f7f7;
    border: 1px solid #ddd;
    margin-bottom: 12px;
    padding: 12px;
    border-radius: 8px;
  }
  .plugin-list a {
    font-weight: bold;
    font-size: 18px;
    text-decoration: none;
    color: #007acc;
  }
  .plugin-list .desc {
    margin-top: 4px;
    color: #555;
  }
</style>

<p>这里是我制作的 Unity 插件集合，每个插件都配有使用教程和示例代码：</p>

<ul class="plugin-list">
  {% for plugin in site.data.plugins %}
    <li>
      <a href="{{ plugin.url }}" target="_blank">{{ plugin.name }}</a>
      <div class="desc">{{ plugin.short_desc }}</div>
    </li>
  {% endfor %}
</ul>
