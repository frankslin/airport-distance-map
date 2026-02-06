# 机场距离 SPA

[English Version](./README.md)

一个单页应用，用于计算机场之间的大圆距离，并在可交互的地球上展示航线。

## 功能
- 覆盖 3000+ 商业航班机场（大型/中型、定期航班）
- 智能搜索与多种输入方式（IATA 代码、城市/机场名、中英文混输）
- 公里/英里实时更新的大圆距离
- 可交互地球：自动旋转到航线位置，并支持拖拽旋转

## 文件
- `airport-distance-app.html` — SPA 主文件（HTML/CSS/JS 单文件）
- `README.md` — 英文说明

## 使用方式
用浏览器直接打开 `airport-distance-app.html`。
也可以使用线上版本：
`https://frankslin.github.io/airport-distance-map/airport-distance-app.html`

## 数据来源
机场坐标来自 OurAirports 公共数据集，筛选条件为：`large_airport` 与 `medium_airport`、`scheduled_service=yes`、且有有效 IATA 代码。
