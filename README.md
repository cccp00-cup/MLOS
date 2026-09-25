# MLOS · 下载页

macOS 风格桌面套件（**程序坞 / 灵动岛 / 启动台 / 顶部菜单栏**）的下载页。

- 纯静态单页：`index.html`，无任何外部依赖，用浏览器直接打开 `file://` 也能看。
- 四个组件的 `.deb` 下载地址指向各自的 GitHub Releases；均为 GPL-3.0。
- 面向 KDE Plasma 6 / Wayland，架构 amd64。

## 本地预览

```bash
python3 -m http.server 8080
# 浏览器打开 http://localhost:8080
```

## 部署到 GitHub Pages

仓库 **Settings → Pages → Build and deployment**：

- **Source**：`Deploy from a branch`
- **Branch**：`main`，目录 **`/ (root)`**

保存后站点发布在 `https://cccp00-cup.github.io/MLOS/`。

## 更新下载链接

四个下载地址写在 `index.html` 的 `<a class="btn" href="…">` 里。
发布新版本时，把链接中的版本号与文件名、以及卡片上的版本/大小一并替换即可。
