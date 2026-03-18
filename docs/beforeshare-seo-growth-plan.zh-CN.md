# BeforeShare SEO 优先推广执行文档

## 1. 当前站点审计结论

- 首页已经具备高质量落地页骨架：H1、功能区、How It Works、Use Cases、Trust 都已到位。
- 产品核心卖点清晰：`on-device`、`no uploads`、`no data collected` 已形成统一心智。
- 这次改造的重点不是“重做官网”，而是把官网升级成“主题页 + 内容页 + 技术 SEO”的持续导流资产。
- 当前历史缺口主要有 4 个：FAQ 缺失、长尾内容页缺失、canonical/OG/schema 缺失、站点级 `url/baseurl/robots/sitemap` 能力不足。

## 2. 首页关键词映射

| 模块 | 目标关键词 | 当前动作 |
| --- | --- | --- |
| Page title / hero eyebrow | `photo privacy app for iPhone` | 已写入站点标题和首屏眉标 |
| Hero subtitle | `blur faces in photos`, `blur license plates`, `remove EXIF metadata` | 已改为关键词自然覆盖版本 |
| Detects / Features | `remove location from photos`, `on-device photo privacy` | 已把语义扩展进中段文案 |
| FAQ | 问题型搜索词 | 已新增 6 个问题型入口 |
| Guides section | 高意图长尾搜索 | 已新增 Guides 区块直链 3 篇文章 |

## 3. 第一批内容页与目标词

### 3.1 How to Blur Faces in Photos on iPhone

- 主词：`blur faces in photos iphone`
- 辅词：`blur faces in photos`
- 辅词：`hide face in photo iphone`

### 3.2 How to Remove EXIF Metadata from Photos on iPhone

- 主词：`remove exif from photo iphone`
- 辅词：`remove metadata from photos iphone`
- 辅词：`remove location from iphone photos`

### 3.3 How to Hide License Plates in Photos Before Sharing

- 主词：`blur license plate in photo`
- 辅词：`hide license plate in photo`
- 辅词：`remove plate from photo iphone`

## 4. 技术 SEO 改造清单

- 已补 `url`、`baseurl`、`lang`、`default_keywords`、`default_og_image`。
- 已补 canonical、robots meta、Open Graph、Twitter Card。
- 已补首页 `SoftwareApplication` JSON-LD。
- 已补首页 `FAQPage` JSON-LD。
- 已补文章页 `Article` JSON-LD。
- 已新增 `robots.txt`。
- 已启用 `jekyll-sitemap` 插件配置。

## 5. 内链策略

- 首页 `Features` 和 `Use Cases` 已添加文章入口链接。
- 首页新增 `Guides` 区块，集中承接 3 篇文章。
- Header 和 footer 都已新增 `Guides` 导航。
- 每篇文章正文中都链向另外两篇相关 guide。
- 每篇文章底部都有 App Store CTA 和相关 guide 列表，并回链首页。

## 6. 发布与索引节奏

### 上线当天

- 本地执行 `bundle install`
- 执行 `bundle exec jekyll build`
- 检查首页和 3 篇文章的 meta、canonical、schema
- 部署 GitHub Pages

### 上线后 24 小时内

- 提交首页到 Google Search Console 请求索引
- 提交 `/blog/` 到 Google Search Console 请求索引
- 提交 3 篇文章请求索引

### 上线后 7 天内

- 检查哪些页面已被收录
- 观察首页与文章页 impressions
- 记录从页面跳转 App Store 的点击情况

### 上线后 14 到 30 天

- 根据 Search Console 查询词优化 title 和 intro
- 扩展第 2 批文章选题
- 把效果最好的 guide 做轻量分发到 X、Reddit、Product Hunt 更新贴

## 7. KPI 与复盘频率

| 指标 | 目标 | 复盘频率 |
| --- | --- | --- |
| 首页是否收录 | 收录 | 每周 |
| 3 篇文章是否收录 | 全部收录 | 每周 |
| Search Console impressions | 持续增长 | 每周 |
| 高意图关键词点击 | 出现首批点击 | 每周 |
| 页面到 App Store 点击 | 能看到稳定导流 | 每周 |

## 8. 下一批可扩展选题

- How to Remove Location Data from Photos Before Posting
- How to Clean Private Details From Screenshots on iPhone
- Best Photo Privacy App for iPhone Before Sharing Online
