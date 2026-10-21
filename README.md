# Personal academic website

Public page: https://haibowanglab.github.io/academic/personal/

## 更新网页

编辑 `personal/index.html`，可查找下列注释：

- `EDIT ABOUT`：一至两句研究简介，不包含教育或工作经历。
- `EDIT RESEARCH`：两个研究主题（Detection and imaging、Readout electronics）及简短说明，各配一幅内嵌 SVG 示意图（Fig. 1 含 a、b 两个分图；Fig. 2），仅为原理示意，不含实验数据。
- `EDIT PUBLICATIONS`：论文条目；期刊论文和会议论文合并，按年份倒序。J 表示期刊，C 表示会议。
- `EDIT SERVICE`：审稿等学术服务。

每条论文包含标题、作者、期刊或会议、年份、卷页和 DOI；本人姓名用 `<strong>` 标记。新增论文时，复制一个 `<li class="pub">` 条目，放在对应的 `pub-year` 年份分组内，并设置 `data-kind="journal"` 或 `data-kind="conference"`，以支持筛选；筛选按钮上的数量由脚本自动统计。新增年份时，同时补充 `year-links` 中的年份链接。

新增或修订论文后，同时更新 `personal/publications.bib`，使引用下载与网页一致。论文标识（如 J1、C1）不表示个人贡献或作者角色。

页面为单文件静态 HTML，采用大字号和响应式排版（桌面正文 18px、论文信息 16px），不依赖第三方字体、图片或脚本库；禁用 JavaScript 时仍显示完整论文列表。保存提交后，GitHub Pages 会自动更新。

联系方式和单位信息待确认后再填写。获奖内容暂不加入网页。

网站根目录 `index.html` 是学术网页入口。原路径 `haibo-wang/` 保留自动跳转，后续请维护 `personal/` 目录。
