# 车库造物 · 公开进度看板 v0

静态页展示本周版本、累计用户、次日留存与 changelog。指标可先 example/手填。

## 本地预览

```bash
python3 -m http.server 8080
# 打开 http://127.0.0.1:8080/
```

## 更新指标

编辑 `public/metrics.json` 后硬刷新页面。`retention_d1` 为 null 时显示「待接入」。禁止编造用户数。

## 自测

1. 首页三卡有值，亮点与 changelog 可见
2. 改 `users_total` 刷新即变
3. 去掉或弄坏 json：出现「指标暂不可用」
