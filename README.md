# aiagenti

青岚宗纪移动端骨架，已拆分为 HTML / CSS / JS，并加入基础 PWA 能力，便于在手机浏览器（含 Termux 本地静态服务）中运行。

## 目录结构

- `qingyue_mobile_v6_ui_fix.html`：页面骨架与容器。
- `assets/css/app.css`：所有样式。
- `assets/js/app.js`：游戏 UI 与状态逻辑。
- `assets/js/pwa.js`：PWA 注册入口。
- `manifest.webmanifest`：PWA 清单。
- `sw.js`：离线缓存 Service Worker。

## 本地运行（Termux）

```bash
python -m http.server 8080
```

在手机浏览器访问：`http://127.0.0.1:8080/qingyue_mobile_v6_ui_fix.html`
