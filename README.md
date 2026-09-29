# 吴美琪的个人主页（mickey1331.github.io）

上海交通大学计算机专业大二学生（研究方向：根据自然语言需求描述生成可证明正确的程序代码，NL2Spec）的个人网站源码，基于 [Academic Pages](https://academicpages.github.io/) 模板（上游为 [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) 主题）。
模板自带的示例内容（示例文章、论文、报告、教学、作品集、示例图片与说明文档）已全部清理，仓库现在是空站点骨架。

## 目录结构

| 路径 | 用途 |
| --- | --- |
| `_config.yml` | 站点与作者信息（标题、姓名、头像、邮箱、各类主页链接、社交账号） |
| `_data/navigation.yml` | 顶部导航栏条目 |
| `_data/cv.json` | `cv-json` 页面使用的简历数据 |
| `_pages/` | 单页：首页 `about.md`、简历 `cv.md`、`publications.html`、`talks.html`、`teaching.html`、`portfolio.html`、`markdown.md`（语法说明）等 |
| `_publications/` | 论文，一个文件一条 |
| `_talks/` | 报告，一个文件一条 |
| `_teaching/` | 教学经历，一个文件一条 |
| `_portfolio/` | 作品集条目，一个文件一条 |
| `_posts/` | 博客文章，文件名为 `YYYY-MM-DD-标题.md` |
| `images/` | 站点图片，头像为 `images/profile.png` |
| `files/` | 静态文件（PDF、压缩包等），网址为 `https://mickey1331.github.io/files/文件名` |
| `markdown_generator/` | 由 TSV/CSV 批量生成论文、报告 Markdown 的脚本与 notebook |
| `talkmap/` | 报告地点地图，运行 `talkmap.py` 或 `talkmap.ipynb` 后生成 `talkmap/map.html` |

## 开始使用

1. 编辑 `_config.yml`，把 `title`、`name`、`author` 下的链接（Google Scholar、ORCID 等）和 `url`、`repository` 换成你自己的信息。目前姓名（吴美琪 / Meiqi Wu）、学校（上海交通大学）、专业（计算机/大二）、研究方向（NL2Spec）、邮箱（mickey1331@sjtu.edu.cn）等已填好，其余留空项按需补充。
2. 修改 `_data/navigation.yml`，保留需要的导航项（不需要的整段删除或注释）。默认的 CV 页面是 Markdown 版 `cv.md`，`cv-json` 版本默认隐藏。
3. 按上面的目录结构往 `_publications/`、`_talks/` 等目录里添加内容，格式可参考 `_pages/markdown.md` 与各集合的 `defaults` 配置。
4. 本地预览：

   ```bash
   bundle install
   bundle exec jekyll serve -l -H localhost
   ```

   打开 http://localhost:4000 查看。（也可用仓库自带的 `Dockerfile` / DevContainer：`docker compose up`。）
5. 推送到 GitHub 的 `main` 分支后，GitHub Pages 会自动构建并发布。

## 说明

* 该站点由 Jekyll 构建，内容与主题分离：正文是 Markdown，样式在 `_sass/`、`assets/`、`_includes/`、`_layouts/` 中。
* 模板本体的 bug 报告与更新请提交到上游仓库 [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)；本仓库是在此基础上定制的个人站点，不需要向上游提交 PR。
* 许可证见 `LICENSE`。
