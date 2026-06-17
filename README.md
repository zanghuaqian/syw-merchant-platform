# 盛意旺商户平台 · 交互原型

对账中心与运营中心的 HTML 交互原型，部署于 GitHub Pages 在线预览。

## 在线访问

**统一入口：** https://zanghuaqian.github.io/syw-merchant-platform/

| 模块 | 链接 |
|------|------|
| 对账总览 | [reconciliation-overview/index.html](reconciliation-overview/index.html) |
| 交易订单查询 | [reconciliation-overview/transaction-order-query.html](reconciliation-overview/transaction-order-query.html) |
| 子商户管理 | [sub-merchant-management/index.html](sub-merchant-management/index.html) |

## 产品标注

页面中红色灯泡图标为产品标注，悬停可查看需求说明。标注样式脚本位于 `assets/product-annotation/`。

## 本地预览

直接用浏览器打开根目录 `index.html`，或使用本地静态服务：

```bash
python -m http.server 8080
# 访问 http://localhost:8080
```

## 目录结构

```
├── index.html                      # 统一入口页
├── assets/product-annotation/      # 产品标注 CSS/JS
├── reconciliation-overview/        # 对账中心
└── sub-merchant-management/        # 运营中心
```
