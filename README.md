# 个人博客

一个可直接部署到 GitHub Pages 的静态中文个人博客。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（推荐命名为 `你的用户名.github.io`）。
2. 将本目录提交并推送到仓库的 `main` 分支。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment** 中选择 **GitHub Actions**。
4. 推送完成后，Actions 会自动部署；若仓库名为 `用户名.github.io`，网站地址即为 `https://用户名.github.io`。

## 自定义

- 在页面中将“林默”、邮箱和 GitHub 链接替换成自己的信息。
- 新文章可复制 `posts/a-digital-garden.html`，并在 `posts.html` 与 `index.html` 添加条目。
- 样式集中在 `assets/css/style.css`，主题逻辑在 `assets/js/main.js`。
