# 我的个人网页

这是一个可以直接发布的静态个人主页，不需要后端，也不需要数据库。

## 怎么修改内容

- 打开 `index.html`，把“你的名字”“邮箱”“项目介绍”等文字换成自己的信息。
- 替换 `assets/hero-workspace.png` 可以换成自己的照片或作品图。
- 如果想改颜色和排版，主要修改 `css/styles.css`。

## 免费发布方案

推荐优先使用 GitHub Pages：

1. 注册或登录 GitHub。
2. 创建一个公开仓库，例如 `my-homepage`。
3. 上传这个文件夹里的全部文件。
4. 在仓库里打开 Settings -> Pages。
5. Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`。
6. 保存后等待一会儿，GitHub 会给你一个可以公开访问的网址。

也可以使用 Netlify 或 Cloudflare Pages，把整个文件夹拖进去或连接 GitHub 仓库即可发布。
