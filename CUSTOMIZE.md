# README 替换清单

上传 GitHub 前，请在 `README.md` 中替换以下内容：

1. `Your Paper Title`：GitHub 页面最上方的论文简称或项目名。
2. `Project Name` 与 `Your Full Paper Title`：项目名和论文完整标题。
3. 所有 `href="#"`：替换为论文、arXiv、代码、Demo、模型和数据集链接。
4. `Introduction`：用 1 段话说明研究问题、方法和最重要结果。
5. 三条主要贡献：每条先写加粗关键词，再用一句话给出贡献。
6. `assets/project-logo.svg`：替换成自己的 Logo，或修改 README 中的文件名。
7. `assets/framework-placeholder.svg`：替换成论文框架图，推荐使用 PNG。
8. `assets/results-placeholder.svg`：替换成最能说明结论的结果图。
9. 结果表格、安装命令、使用命令和 BibTeX 引用。

推荐的图片规范：

- 框架图宽度至少 1600 px，PNG 格式，白色或透明背景。
- 结果图宽度至少 1200 px，文字在手机端仍应可辨认。
- 文件名使用小写英文和连字符，例如 `method-overview.png`。
- 图片放在 `assets/` 下，并在 README 中使用相对路径。
- 不要直接粘贴 Word 截图；优先从论文 PDF 导出高清图片。

整理好后可运行：

```powershell
git init
git add .
git commit -m "Add paper README"
git branch -M main
git remote add origin https://github.com/你的用户名/仓库名.git
git push -u origin main
```

