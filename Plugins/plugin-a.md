---
layout: page
title: "插件A"
permalink: /plugins/plugin-a.html
---

## 插件A

**功能**

- 在运行时或编辑模式下一键拍摄场景快照。

**安装**

1. 在 Unity 中打开 Package Manager
2. 点击 “+” → Add package from git URL...
3. 填入：`https://github.com/<username>/plugin-a.git`

**使用示例**

```csharp
SnapshotTaker.Capture("MySnapshot.png");
```