# GitHub Pages 上线说明

## 关键要求

GitHub Pages 发布源的顶层必须直接有 `index.html`。

正确结构：

```text
index.html
showcase.html
styles.css
app.js
assets/
.github/
.nojekyll
```

错误结构：

```text
OPC_GitHub_UI_Update/index.html
```

如果 `index.html` 被套在文件夹里，访问仓库 Pages 地址会显示 404。

## GitHub 页面操作

1. 打开仓库首页。
2. 删除旧的 ZIP 和旧的外层文件夹。
3. 打开本包文件夹，把里面的所有文件全选上传到仓库根目录。
4. 进入 `Settings → Pages`。
5. 推荐选择：

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

6. 保存后等待 1–3 分钟。

访问地址通常为：

```text
https://你的用户名.github.io/仓库名/
```
