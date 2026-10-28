# 袁帅的个人主页

算法工程师 / OCR / 文档智能方向的一页式个人主页。

线上地址：https://yuanshuai.github.io

项目展示中的三个项目无公开线上演示，源码统一见
https://github.com/Yuanshuai/shuai 。

## 技术说明

- 纯静态 HTML / CSS / JavaScript，无构建步骤、无外部 CDN 依赖
- 支持深色 / 浅色模式、响应式布局、滚动入场动画
- 头像与简历均为本地文件，部署后可直接下载

## 本地预览

```powershell
cd C:\Users\86195\Desktop\Yuanshuai-homepage
python -m http.server 8000
```

访问 `http://localhost:8000`。

## 内容修改

- 个人信息、技能、项目、经历：`index.html`
- 头像：`avatar.png`
- 简历：`resume.pdf`

## 部署

仓库名 `Yuanshuai.github.io`，GitHub Pages 使用 `main` 分支根目录发布。
推送后等待 1-2 分钟即可访问。
