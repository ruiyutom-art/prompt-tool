# AI 提示词工具

这是一个可直接部署到 GitHub Pages 的静态网页项目。

## 文件说明

- `index.html`: 网站首页，由原始 `page.html` 重命名而来。
- `.nojekyll`: 告诉 GitHub Pages 不要使用 Jekyll 处理静态文件。

## 发布到 GitHub Pages

1. 打开 https://github.com/new
2. 创建一个新仓库，例如 `prompt-tool`。建议选择 `Public`，这样 GitHub Pages 免费可访问。
3. 进入新仓库，点击 `Add file` -> `Upload files`。
4. 上传本目录里的 `index.html`、`.nojekyll` 和 `README.md`，然后点击 `Commit changes`。
5. 进入仓库的 `Settings` -> `Pages`。
6. 在 `Build and deployment` 里选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
7. 点击 `Save`，等待 1-3 分钟。

发布完成后，访问地址通常是：

```text
https://你的GitHub用户名.github.io/仓库名/
```

例如仓库名是 `prompt-tool`，用户名是 `alice`，地址就是：

```text
https://alice.github.io/prompt-tool/
```
