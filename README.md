# hiit

HIIT 随身跟练与打卡。仓库根目录的 `index.html` 是完整单页应用，浏览器打开即可使用。

## 在线站点

合并到 `main` 后，在仓库 **Settings → Pages** 选择 **Deploy from a branch**，分支 `main`，目录 **`/ (root)`**。启用后的地址：

https://deityhp.github.io/hiit/

页面依赖的 Tailwind、Font Awesome 和 Google Fonts 仍从各自的公共 CDN 加载，没有额外统计或后端。

## 数据

动作配置、打卡记录和休息时长只写在当前浏览器的 `localStorage`：

- `hiit_exercises_config`
- `hiit_checkins_history`
- `hiit_rest_duration`

这些数据不会上传。换浏览器、清站点数据或用隐私模式会看不到原来的记录。

本地预览：用浏览器直接打开 `index.html`。
