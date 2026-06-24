# TXT 章节净化器

一个纯前端、单文件、离线运行的 TXT 小说章节清理工具。

## 在线访问

- GitHub Pages：<https://laishengli120.github.io/txt-chapter-cleaner/>
- CDN 备用入口：<https://cdn.jsdelivr.net/gh/laishengli120/txt-chapter-cleaner@main/index.html>

如果国内访问 GitHub Pages 不稳定，可以优先尝试 CDN 备用入口；也可以下载 `index.html` 后直接双击本地打开，功能完全离线可用。

## 使用

- 直接打开 `index.html` 或 `outputs/章节净化器.html`
- 支持拖放/选择 TXT，也支持直接粘贴文本
- 清理重复章节标题、分页标题、翻页提示、站点页脚、网址推广等噪声
- 提供“修改明细 / 对照预览 / 清理结果”三种视图
- 可复制或下载 UTF-8 BOM 的净化结果

所有处理都在浏览器本地完成，不上传文件、不依赖网络。

## 国内访问建议

这个工具是纯静态单文件，后续如果要让国内访问更稳，推荐部署到阿里云 OSS / 腾讯云 COS 静态网站，并绑定已备案域名和 CDN。没有备案域名时，GitHub Pages 与境外 CDN 的速度和可达性会受网络环境影响。

## 文件

- `index.html`：便于 GitHub Pages 或浏览器直接打开的入口
- `outputs/章节净化器.html`：原始交付文件名
