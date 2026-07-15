# AI Product Live Operations Review

这是一个用于作品集和面试展示的静态复盘网站，主题为 AI 产品直播运营复盘。项目以脱敏方式保留了完整的页面设计、复盘框架、分析逻辑、运营结论和 AI 提效方法，适合作为内容运营、直播运营、增长运营和 AI 工作流实践的展示型作品。

## 项目概述

该项目通过一个长页静态网站，系统展示某阶段 AI 产品直播运营的复盘结果，重点覆盖以下内容：

- 直播间定位、目标和内容机制
- 核心增长结果与关键指标变化
- 十六场直播的经验总结与问题复盘
- 互动转化、人群画像和未来运营规划
- AI 在海报、文案、复盘和内容工作流中的提效方式
- 场次海报与详细数据入口，方便查看单场表现

页面内容已做脱敏处理，适合公开展示给招聘方、面试官或合作方。

## 技术栈概述

- HTML5
- CSS3
- 原生 JavaScript
- Chart.js CDN
- SVG 静态素材

## 项目特点

- 纯静态站点，无需后端服务
- 主要内容直接写在 HTML 中，部署简单
- 通过 Chart.js 展示复盘数据与趋势信息
- 适合作为 GitHub Pages 或 Netlify 静态项目发布
- 包含作品集场景下常见的脱敏说明与视觉包装

## 文件结构

```text
.
├── index.html
├── report_preview.html
├── assets/
│   ├── sanitized-hero.svg
│   ├── posters/
│   └── thumbnails/
└── README.md
```

## 运行方式

这是一个纯静态项目，直接在浏览器中打开 [index.html](/Users/jiaojiao/Documents/Codex/2026-07-15/wo/work/site2/live-review-report/index.html) 即可预览。

如果你想通过本地服务预览，也可以在项目目录下运行任意静态服务器，例如：

```bash
npx serve .
```

或：

```bash
python3 -m http.server 8000
```

然后访问本地地址查看页面。

## 部署建议

这个项目适合部署到以下平台：

- GitHub Pages
- Netlify
- Vercel 静态站模式

由于它不依赖后端接口，所以非常适合公开展示，同时继续保持代码仓库私有或公开都可以。

## 备注

- `index.html` 与 `report_preview.html` 当前内容一致，可按展示需要保留一个主入口
- 图表依赖外部 Chart.js CDN，部署时需要网络可访问该资源
- 页面中的业务名称、日期、人员和数据细节已脱敏
