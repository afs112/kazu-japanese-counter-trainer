# KAZU · 日语数量词与音变学习网站

一个可离线使用的中文日语数量词教学网站。课程循序引入和语计数、常见助数词、促音、浊音、半浊音与读法差异，并通过图解、标记表和独立输入练习进行巩固。

## 立即使用

- **在线网站**：启用 GitHub Pages 后，访问 https://afs112.github.io/kazu-japanese-counter-trainer/
- **离线学习**：下载本仓库的 `index.html` 并用浏览器打开。
- 学习进度存于浏览器 `localStorage`，不上传服务器，也不会自动跨设备同步。

## 启用 GitHub Pages

1. 如果 GitHub 账号套餐不支持私有仓库发布 Pages，请到 **Settings → General → Danger Zone → Change repository visibility** 将仓库调整为 **Public**（这会公开代码；仅在愿意公开时操作）。
2. 打开 **Settings → Pages**。
3. **Build and deployment → Source** 选择 `Deploy from a branch`。
4. 选择 `main` 分支和 `/(root)` 文件夹，点击 **Save**。
5. 等 GitHub Pages 显示部署完成后，打开 https://afs112.github.io/kazu-japanese-counter-trainer/。

> 提醒：上述网站地址只在 Pages 部署完成后才生效。如果打算保留仓库私有，请先确认你的 GitHub 方案是否支持私有仓库的 GitHub Pages。

## 项目文件

- `index.html`：完整网站，HTML / CSS / JavaScript 均已内嵌。
- `.nojekyll`：告知 GitHub Pages 不需 Jekyll 构建。
- `README.md`：使用和部署说明。

本项目无需 npm、构建命令或外部 CDN。
