# [BRANDNAME] — 面向欧洲市场的高性价比滑雪服品牌

> **状态**：上线前准备阶段
> **目标市场**：法国 + 爱尔兰（第一阶段）
> **商业模式**：DTC（直接面向消费者）通过 Shopify 独立站 + TikTok 营销

## 项目结构

```
SkiShop/
├── brand/
│   └── brand-guidelines.md        # 品牌规范：配色、字体、品牌调性
├── content/
│   ├── pages/                     # 网站页面文案（英文，直接粘贴到Shopify）
│   │   ├── about-us.md            # 关于我们
│   │   ├── shipping-policy.md     # 配送政策
│   │   ├── returns-policy.md      # 退换货政策
│   │   ├── size-guide.md          # 尺码指南
│   │   ├── faq.md                 # 常见问题
│   │   └── privacy-policy.md      # 隐私政策（GDPR合规）
│   └── tiktok/
│       └── content-calendar.md    # TikTok内容日历（8月-3月）
├── products/
│   ├── shopify-products-template.csv  # Shopify批量导入CSV模板
│   └── product-descriptions.md        # 产品描述文案模板
└── docs/
    └── compliance-checklist.md    # EU合规清单（GPSR、纺织标签、IOSS）
```

## 快速上手

1. **品牌名**：确定品牌名后，全局替换所有文件中的 `[BRANDNAME]` 占位符
2. **Shopify**：在 shopify.com 注册账号，导入 `products/shopify-products-template.csv`
3. **页面文案**：将 `content/pages/` 中的内容复制到 Shopify 页面编辑器（英文，给欧洲客户看）
4. **TikTok**：按照 `content/tiktok/content-calendar.md` 中的内容日历执行

## 核心数据

- **MVP产品**：3款产品（男款雪服、女款雪服、通用雪裤）
- **SKU数量**：共30个（3款 × 2色 × 5码）
- **定价**：雪服 €129-139，雪裤 €89-99（单件控制在€150以内，走IOSS通道）
- **市场**：先做法国+爱尔兰，再扩展到德语区（德国、奥地利）

## 重要提醒

- 所有价格必须含VAT（增值税）显示——这是EU法律要求
- IOSS仅适用于单票价值≤€150的订单（所以先推单件，不推套装）
- 纺织品标签必须使用目标国语言（卖法国→法语标签）
- GPSR（通用产品安全法规）要求指定EU境内负责人——你的爱尔兰公司可以担任

## 文件语言说明

| 文件类型 | 语言 | 原因 |
|----------|------|------|
| 内部文档（README、品牌规范、内容日历、合规清单） | 中文 | 方便自己阅读和使用 |
| 网站页面文案（`content/pages/` 下的6个文件） | 英文 | 给欧洲客户看，直接粘贴到Shopify |
| Shopify产品CSV | 英文 | Shopify导入格式要求 |
