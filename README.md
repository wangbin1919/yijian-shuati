# 一建刷题题库 H5

一键刷题网页版（纯静态，零后端）。

## 文件说明

- `index.html` — 刷题页面（内联 CSS/JS，唯一外部引用为相对路径 `zhenti-data.js`，天然兼容 GitHub Pages 子路径部署）
- `zhenti-data.js` — 题库数据（5059 题，12 科目，2015–2025 年真题）

## 部署

GitHub Pages 部署方式：把本目录内容推送到仓库 main 分支根目录，仓库 Settings → Pages → Source 选 `Deploy from a branch` → `main` → `/ (root)`。

访问地址：`https://<用户名>.github.io/<仓库名>/`

子路径兼容说明：页面资源全部使用相对路径（`zhenti-data.js`），CSS/JS 内联，无外部图片与接口依赖，在任意子路径下均可正常加载。