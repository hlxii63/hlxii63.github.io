# 📄 把游戏放到 GitHub Pages（朋友直接开网址玩）

`index.html` 就是完整游戏（单文件版，含全部功能）。

## 上传步骤（手机也能操作）

1. 打开你的仓库：https://github.com/hlxii63/hlxii63.github.io
2. 点 **Add file → Upload files**
3. 选择本目录的 `index.html` 上传 → 点 **Commit changes**
4. 等 1~2 分钟，打开 **https://hlxii63.github.io/** 就是游戏了

> 如果仓库里已经有 index.html，直接**覆盖**即可（或先删掉再传）。

## 之后

- 朋友们不用装 App，**浏览器打开 https://hlxii63.github.io/ 就能玩**
- 社区功能用「GitHub Gist」存储方式（见主 README），全部免服务器
- 以后更新游戏：把新的 `www/index-standalone.html` 重新覆盖到仓库根目录的 index.html

## 常见问题

| 现象 | 解决 |
|---|---|
| 打开网址是 404 / 旧页面 | 等 1~2 分钟（Pages 构建）；确认文件在仓库根目录且叫 index.html |
| 页面空白 | 浏览器开「桌面版网站」或换 Chrome 试试；按 F12 看控制台报错 |
| 想用自己的域名 | 仓库 Settings → Pages → Custom domain |
