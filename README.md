# 上海出发浙东山海端午三日游

静态 HTML 攻略页，面向手机阅读和分享。

## 在线地址

https://jooewood.github.io/duanwu/

## 文件说明

- `index.html`：主页面，GitHub Pages 直接发布这个文件。
- `.nojekyll`：避免 GitHub Pages 走 Jekyll 处理。

## 导出 PDF

打开页面后点 `导出 PDF`，在系统打印窗口里选择“保存为 PDF”。导出前页面会自动展开所有模块。若内置浏览器不弹打印窗口，请用系统浏览器打开页面后再导出。

## 更新方式

修改 `index.html` 后提交并推送到 `main` 分支：

```bash
git add index.html README.md
git commit -m "Update guide"
git push
```

GitHub Pages 会自动发布，通常几十秒到几分钟生效。页面以 `index.html` 为唯一维护对象。
