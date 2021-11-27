# The Open Manual Repository



### How to Update

Document is written in Markdown and deployed with Jekyll.

[Markdown Reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
|
[Basic Tutorial on GitHub](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
|
[About GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)


#### Controls for PDF Output

You can use `class="print--hidden"` to hide content from "Print to PDF" output.  
`class="print--d-none"` is also available, note that this will change page layout.

If you want to add page break for PDF explicitly, use: `<div class="print--page-break"></div>`


### Template for New Page

File extension must be `.md`

```yaml
---
title: "Page Title"
lang: en
date: 2021-12-02
author:
- "You"
- "Prior to You"
---

# Contents written in Markdown
```
