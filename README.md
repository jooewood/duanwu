# 上海出发浙东山海端午三日游

静态 HTML 攻略页，面向手机阅读和分享。

## 在线地址

https://jooewood.github.io/duanwu/

## 文件说明

- `index.html`：主页面，GitHub Pages 直接发布这个文件。
- `.nojekyll`：避免 GitHub Pages 走 Jekyll 处理。
- `output/`：历史导出的 PDF 存放目录。后续 PDF 不自动维护。

## 更新方式

修改 `index.html` 后提交并推送到 `main` 分支：

```bash
git add index.html README.md
git commit -m "Update guide"
git push
```

GitHub Pages 会自动发布，通常几十秒到几分钟生效。

## PDF 导出

PDF 由浏览器手动导出：

1. 打开在线页面或本地页面。
2. 点击页面里的“打印 / 导出 PDF”。
3. 在浏览器打印面板中选择“保存为 PDF”。

不要把 PDF 当作主要维护对象；以 `index.html` 为准。
