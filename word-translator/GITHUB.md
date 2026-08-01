# 📤 上传到 GitHub 部署

## 步骤：

1. **打开 GitHub**：https://github.com/new
2. **创建新仓库**：
   - 仓库名：`word-translator`（任意你喜欢的名字）
   - 设置为 **Public**（公开）
   - ⚠️ **不要勾选** "Add a README file"
   - ⚠️ **不要勾选** "Add .gitignore"
   - ⚠️ **不要勾选** "Choose a license"
3. 点击 **Create repository**

4. **复制仓库地址**（类似）：`https://github.com/你的用户名/word-translator.git`

5. **在终端执行**（替换你的用户名）：
```bash
cd /vol2/@apphome/trim.openclaw/data/workspace/word-translator
git remote add origin https://github.com/你的用户名/word-translator.git
git branch -M main
git push -u origin main
```

6. **完成！** 去 GitHub 仓库设置 Pages：
   - Settings → Pages
   - Source: `main` branch, folder: `/ (root)`
   - 保存

7. **等待 1-2 分钟**，访问：`https://你的用户名.github.io/word-translator/`

---

**需要我帮你创建 GitHub 仓库吗？** 🐾
