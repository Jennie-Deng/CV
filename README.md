# Shuangyan Deng Academic Homepage

双艳的个人学术主页与简历项目。这个仓库包含 Shuangyan Deng 的个人学术主页，
已经填入邮箱、简介、研究方向、教育经历、访问经历、奖项和论文列表。项目是
纯静态文件，可以直接发布到 GitHub Pages。

## 当前内容

- 姓名：Shuangyan Deng
- 身份：Ph.D. Student in Statistics
- 机构：University of Auckland
- 邮箱：sden118@aucklanduni.ac.nz
- Google Scholar：https://scholar.google.com/citations?user=f1wok9gAAAAJ&hl=en
- ORCID：https://orcid.org/0009-0004-4395-2877
- LinkedIn：https://www.linkedin.com/in/shuangyan-deng-720510300/
- GitHub：https://github.com/Jennie-Deng

## 可选补充

- 头像：已添加到 `assets/profile.jpg`，主页会自动显示。
- CV：把 PDF 放到根目录并命名为 `cv.pdf`，然后把 CV 按钮链接从邮箱改成
  `cv.pdf`。
- 当前远程仓库：`git@github.com:Jennie-Deng/CV.git`

## 发布到 GitHub Pages

当前仓库是 `Jennie-Deng/CV`。如果在这个仓库启用 GitHub Pages，常见页面地址是：

```text
https://jennie-deng.github.io/CV/
```

推荐发布方式是 GitHub Actions。本仓库已经包含 `.github/workflows/pages.yml`，
每次推送到 `main` 后会自动发布静态网页。

发布步骤：

1. 打开仓库的 `Settings` > `Pages`。
2. 找到 `Build and deployment`。
3. 如果能看到发布方式，选择 `GitHub Actions`。
4. 如果页面没有 `Source`，看是否有 `GitHub Actions`、`Workflow`、`Actions`
   或 `Deploy from a branch` 相关选项；选择 GitHub Actions 即可。
5. 打开仓库的 `Actions` 页面，查看 `Deploy GitHub Pages` 是否运行成功。
6. 几分钟后访问：

   ```text
   https://jennie-deng.github.io/CV/
   ```

如果希望网址是账户根主页 `https://jennie-deng.github.io/`，GitHub 仓库名通常需要是
`Jennie-Deng.github.io`。如果希望使用 `shuangyan-deng.github.io`，需要确认这是可用
GitHub Pages 账户/组织名或已正确配置的自定义域。

## 用 Git 推送发布

如果本地已经连接远程仓库，可以推送 `main` 分支：

```text
git push -u origin main
```
