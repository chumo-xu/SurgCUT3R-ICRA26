# SurgCUT3R 项目网站（静态页面）

本文件夹是 **SurgCUT3R** 论文对应的项目网站源文件（纯静态 HTML/CSS/JS，无需构建）。

## 你需要改哪里

- **主页内容**：编辑 `index.html`
- **样式**：编辑 `static/css/index.css`
- **交互（例如 BibTeX 复制按钮）**：编辑 `static/js/index.js`

## 放置论文 PDF（让 “Paper” 按钮可用）

把论文 PDF 放到下面路径（自己创建目录即可）：

- `static/pdfs/paper.pdf`

然后打开 `index.html` 里的 Paper 按钮链接会自动生效（目前指向 `static/pdfs/paper.pdf`）。

## 你还需要补的关键信息（SEO/分享卡片）

`index.html` 的 `<head>` 里仍保留了少量 TODO，需要你填成真实地址：

- `og:url`、结构化数据里的 `url`
- `og:image`（建议把 1200×630 的预览图放到 `static/images/social_preview.png`，并把域名替换成你实际部署地址）
- Code 链接（当前是 “Code (Coming Soon)” 的禁用按钮）

## 说明

此页面最初基于 Academic Project Page Template（Nerfies 风格）改写而来。
