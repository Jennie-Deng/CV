# Shuangyan Deng Academic Homepage

这是 Shuangyan Deng 的个人学术主页，已经填入邮箱、简介、研究方向、教育经历、
访问经历、奖项和论文列表。项目是纯静态文件，可以直接发布到 GitHub Pages。

## 当前内容

- 姓名：Shuangyan Deng
- 身份：Ph.D. Student in Statistics
- 机构：University of Auckland
- 邮箱：sden118@aucklanduni.ac.nz
- Google Scholar：https://scholar.google.com/citations?user=f1wok9gAAAAJ&hl=en
- ORCID：https://orcid.org/0009-0004-4395-2877
- LinkedIn：https://www.linkedin.com/in/shuangyan-deng-720510300/

## 可选补充

- 头像：把照片放到 `assets/profile.jpg`，然后把 `index.html` 里的头像占位块
  换成图片标签。
- CV：把 PDF 放到根目录并命名为 `cv.pdf`，然后把 CV 按钮链接从邮箱改成
  `cv.pdf`。
- GitHub：提供 GitHub 用户名后，可以把仓库名设为
  `GITHUB-USERNAME.github.io`。

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库，推荐名称：

   ```text
   GITHUB-USERNAME.github.io
   ```

2. 上传这些文件：

   ```text
   index.html
   styles.css
   404.html
   .nojekyll
   robots.txt
   README.md
   assets/.gitkeep
   ```

3. 打开仓库的 `Settings` > `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，文件夹选择 `/root`，保存。
6. 几分钟后访问：

   ```text
   https://GITHUB-USERNAME.github.io
   ```

## 用 Git 推送发布

如果本地已经连接远程仓库，可以推送 `main` 分支：

```text
git push -u origin main
```

如果还没连接远程仓库，先添加远程地址：

```text
git remote add origin https://github.com/GITHUB-USERNAME/GITHUB-USERNAME.github.io.git
git push -u origin main
```
