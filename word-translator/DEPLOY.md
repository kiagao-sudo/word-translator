# 🚀 部署到 Netlify（最简单方式）

## 方式一：Netlify Drop（推荐，无需安装任何东西）

1. **打开浏览器**，访问：https://app.netlify.com/drop
2. **拖拽这个文件夹**：`word-translator`
3. **等待 1-2 分钟**，Netlify 会生成访问链接
4. **完成！** 你的翻译器上线了

## 方式二：使用 Netlify CLI（需要安装）

如果你已经安装了 Netlify CLI：
```bash
npm install -g netlify-cli
cd word-translator
netlify deploy --prod
```

## 方式三：GitHub Pages（免费）

1. 将 `word-translator` 文件夹上传到 GitHub 仓库
2. 进入仓库 Settings → Pages
3. 选择 branch：`main` 或 `master`，folder：`/ (root)`
4. 保存，等待 1-2 分钟
5. 访问：`https://你的用户名.github.io/仓库名/`

---

**推荐方式一**，最简单快速！ 🎉
