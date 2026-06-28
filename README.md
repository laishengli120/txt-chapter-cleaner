# TXT 章节净化器

一个纯前端、单文件、离线运行的 TXT 小说章节清理工具。它适合在本地清理重复章节标题、分页标题、翻页提示、站点页脚、推广网址等噪声，并保留可追溯的修改明细。

## 在线访问

- GitHub Pages：<https://laishengli120.github.io/txt-chapter-cleaner/>
- 第三方 HTML 预览备用：<https://raw.githack.com/laishengli120/txt-chapter-cleaner/main/index.html>
- CDN 下载备用：<https://cdn.jsdelivr.net/gh/laishengli120/txt-chapter-cleaner@main/index.html>

如果国内访问 GitHub Pages 不稳定，可以尝试备用地址；如果 CDN 地址在浏览器中显示源码，请另存为 `index.html` 后本地打开。

## 功能

- 拖放或选择 TXT 文件
- 直接粘贴文本并清理
- 自动识别和移除常见章节噪声
- 提供“修改明细 / 对照预览 / 清理结果”三种视图
- 复制或下载带 UTF-8 BOM 的清理结果
- 完全浏览器本地处理，不上传文件

## 使用方法

1. 打开 `index.html` 或 `outputs/章节净化器.html`。
2. 上传 TXT 文件，或把原文粘贴到输入框。
3. 查看修改明细和对照预览。
4. 复制结果或下载净化后的 TXT。

## 文件说明

```text
index.html              # GitHub Pages 和本地浏览入口
outputs/章节净化器.html  # 原始交付文件名
```

## 部署建议

这是一个纯静态单文件工具，可以部署到 GitHub Pages、Netlify、Vercel、阿里云 OSS、腾讯云 COS 等静态托管服务。若希望国内访问稳定，建议使用已备案域名配合国内对象存储和 CDN。
