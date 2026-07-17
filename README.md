# Pengfei He — Personal Website

这是一个无框架的静态个人主页，可直接部署到 GitHub Pages。内容根据个人简历整理，默认未公开住址、手机号和微信。

## 本地预览

在当前目录运行：

```bash
python3 -m http.server 8000
```

浏览器访问 `http://localhost:8000`。

## 部署到 GitHub Pages

1. 在 GitHub 新建名为 `你的用户名.github.io` 的公开仓库。例如用户名是 `pengfeihe`，仓库名就是 `pengfeihe.github.io`。
2. 把本目录中的 `index.html`、`styles.css`、`script.js` 和 `README.md` 推送到仓库的 `main` 分支。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，然后保存。
5. 等待一两分钟后访问 `https://你的用户名.github.io`。

常用命令：

```bash
git init
git add .
git commit -m "Create personal website"
git branch -M main
git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
git push -u origin main
```

## 发布前建议补充

- 将论文条目链接到 DOI、arXiv 或会议页面。
- 加入 GitHub 与 Google Scholar 链接。
- 如果需要提供简历下载，建议先制作一份删除住址、手机号和微信的公开版 PDF。
- 核对仍在审稿中的论文是否适合公开写出状态与成绩。

