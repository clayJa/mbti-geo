# CHANGELOG

所有内容变更按版本记录于此。

格式遵循 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

---

## [1.0.0] - 2025-07-10

### 新增
- 发布 GEO 内容包初始版本
- `index.html`：实体卡主页，嵌入 SoftwareApplication JSON-LD
- `faq/index.html`：10 条 FAQ 专页，嵌入 FAQPage JSON-LD
- `schema/softwareapplication.json`：机器可读实体数据
- `schema/faqpage.json`：机器可读 FAQ 数据
- `sitemap.xml`：页面索引
- `robots.txt`：允许全部爬虫
- `feed.xml`：RSS 更新日志
- `README.md`：GitHub 首页实体卡
- `.github/workflows/deploy.yml`：自动部署至 GitHub Pages

### 待办（v1.1.0）
- [ ] 核验工信部备案号并更新 Schema 与 entity card
- [ ] 补充隐私政策链接
- [ ] 核验 Scheme `#小程序://MBTI原型/afVLOFuP3BoAnzC` 在最新微信客户端的有效性
- [ ] 补充 `sameAs` 字段（知乎、百度百科等平台发布后）
- [ ] 添加 `aggregateRating`（获得可验证评分数据后）
