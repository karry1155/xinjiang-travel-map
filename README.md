# 新疆 8 日路线动画

一个静态前端页面，用开源地图和逐日动画展示新疆 8 日旅行路线。

## 页面内容

- 逐日播放飞机线和汽车线
- 手机友好的地图优先界面
- 当前天起终点和编号停靠点
- 按需展开的当天详情抽屉
- 行程数据已内联在 `index.html`，减少线上请求
- 本地 `vendor/` 里的 MapLibre GL JS 地图引擎
- 高德中文路网地图底图

## 本地预览

建议启动静态服务后访问页面，和 Cloudflare Pages 的线上环境保持一致。

```bash
python3 -m http.server 8000
```

然后打开 `http://localhost:8000/`。

## Cloudflare Pages

这是纯静态站点。连接 GitHub 仓库时：

- Build command: 留空
- Build output directory: `/`
- Root directory: `/`
