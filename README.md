# 榆次天气 iPhone 主屏幕网页 App

这是一个适合 iPhone Safari「添加到主屏幕」的天气网页 App。

## 本地预览

直接用浏览器打开 `index.html` 即可预览。

## 部署

推荐免费部署到 Vercel、Netlify 或 GitHub Pages。部署后用 iPhone Safari 打开 HTTPS 地址，点分享按钮，选择「添加到主屏幕」。

## 数据源

当前版本使用 Open-Meteo 免密接口，地点固定为山西晋中榆次/介休/当前位置。后续如果你申请了和风天气或彩云天气 API，可以把 `index.html` 里的 `apiUrl` 和解析逻辑替换成对应接口。

## 功能

- 当前天气与体感温度
- 湿度、风速、今日降雨概率
- 未来 7 天横向滑动预报
- 点击单日查看详情
- 降雨风险提示
