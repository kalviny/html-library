# html-library

这个仓库长期存放**经确认可公开的 HTML 页面**。

网站由 GitHub Pages 从 `main` 分支的仓库根目录发布。

## 发布结构

```
index.html                    中文目录首页
.nojekyll                     让 GitHub Pages 原样发布静态文件
papertrails-workflow/
  index.html                  拆解 Papertrails：@xikhar 的 AI 制作流程（学习页）
```

- 根目录的 [`index.html`](index.html) 是中文目录首页。
- 每篇页面放在独立目录下的 `index.html` 里，这样访问路径保持稳定。
- 当前已有：[`papertrails-workflow/index.html`](papertrails-workflow/index.html)。

## 可以放什么

只放准备公开的网页，以及发布必需的静态文件（如 `.nojekyll`）。

**不要**放：

- 本地日志、CLI 记录
- 登录信息、密钥、令牌
- 源材料、原始抓取数据
- 未公开的草稿
- 聊天记录或任何个人信息

## 关于第三方内容

部分页面引用了第三方的文字、截图或媒体链接。这些内容的版权归原作者所有。

本仓库**不对**任何第三方原图、原文或其他内容授予使用许可。也不要在仓库中添加会覆盖第三方内容的许可证声明。
