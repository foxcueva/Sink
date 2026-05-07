# ⚡ Sink

**A Simple / Speedy / Secure Link Shortener with Analytics, 100% run on Cloudflare.**

<a href="https://trendshift.io/repositories/10421" target="_blank">
  <img
    src="https://trendshift.io/api/badge/repositories/10421"
    alt="miantiao-me/Sink | Trendshift"
    width="250"
    height="55"
  />
</a>
<a href="https://news.ycombinator.com/item?id=40843683" target="_blank">
  <img
    src="https://hackernews-badge.vercel.app/api?id=40843683"
    alt="Featured on Hacker News"
    width="250"
    height="55"
  />
</a>
<a href="https://hellogithub.com/repository/57771fd91d1542c7a470959b677a9944" target="_blank">
  <img
    src="https://abroad.hellogithub.com/v1/widgets/recommend.svg?rid=57771fd91d1542c7a470959b677a9944&claim_uid=qi74Zp23wYKeAVB&theme=neutral"
    alt="Featured｜HelloGitHub"
    width="250"
    height="55"
  />
</a>
<a href="https://www.uneed.best/tool/sink" target="_blank">
  <img
    src="https://www.uneed.best/POTW1.png"
    alt="Uneed Badge"
    width="250"
    height="55"
  />
</a>

[<img src="https://devin.ai/assets/deepwiki-badge.png" alt="DeepWiki" height="20"/>](https://deepwiki.com/miantiao-me/Sink)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F69652?style=flat&logo=cloudflare&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat&logo=nuxtdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=shadcnui&logoColor=white)

![Hero](./public/image.png)

---

## ✨ 特性

- **🔗 网址缩短：** 将您的网址压缩至最短。
- **📈 数据统计：** 监控链接数据并收集有价值的统计信息。
- **☁️ 无服务器 (Serverless)：** 无需传统服务器即可部署。
- **🎨 自定义短链后缀 (Slug)：** 支持个性化后缀及大小写敏感。
- **🪄 AI 生成后缀：** 利用 AI 生成短链后缀。
- **⏰ 链接过期：** 为您的链接设置过期时间。
- **📱 设备路由：** 将 iOS/Android 用户重定向至不同的网址（如应用商店链接）。
- **🖼️ OpenGraph 预览：** 自定义社交媒体预览的标题、描述和图片。
- **📊 实时数据分析：** 动态 3D 地球可视化与实时事件日志。
- **🔲 二维码：** 为您的短链接生成二维码。
- **📦 导入/导出：** 通过 JSON/CSV 文件进行批量迁移。
- **🌍 多语言：** 控制台全面支持国际化 (i18n)。
- **🌙 暗黑模式：** 支持浅色、深色及系统主题。


## 🪧 Demo

Experience the demo at [Sink.Cool](https://sink.cool/dashboard). Log in using the Site Token below:

```txt
Site Token: SinkCool
```

<details>
  <summary><b>Screenshots</b></summary>
  <img alt="Analytics" src="./docs/images/sink.cool_dashboard.png"/>
  <img alt="Links" src="./docs/images/sink.cool_dashboard_links.png"/>
  <img alt="Link Analytics" src="./docs/images/sink.cool_dashboard_link_slug.png"/>
</details>

## 🧱 Technologies Used

- **Framework**: [Nuxt](https://nuxt.com/)
- **Database**: [Cloudflare Workers KV](https://developers.cloudflare.com/kv/)
- **Analytics Engine**: [Cloudflare Workers Analytics Engine](https://developers.cloudflare.com/analytics/)
- **UI Components**: [shadcn-vue](https://www.shadcn-vue.com/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Deployment**: [Cloudflare](https://www.cloudflare.com/)

## 🚗 Roadmap [WIP]

We welcome your contributions and PRs.

- [x] Browser Extension - [Sink Tool](https://github.com/zhuzhuyule/sink-extension)
- [x] Chrome Extension - [Sink Quick Shorten](https://chromewebstore.google.com/detail/sink-quick-shorten/emlojomjpenjgkaphajcokijobpkejih)
- [x] Raycast Extension - [Raycast-Sink](https://github.com/foru17/raycast-sink)
- [x] Apple Shortcuts - [Sink Shortcuts](https://s.search1api.com/sink001)
- [x] iOS App - [Sink](https://apps.apple.com/app/id6745417598)
- [ ] Enhanced Link Management (with Cloudflare D1)
- [ ] Analytics Enhancements (Support for merging filter conditions)
- [ ] Dashboard Performance Optimization (Infinite loading)
- [ ] Units Test

## 🏗️ Deployment

> Video tutorial: [Watch here](https://www.youtube.com/watch?v=MkU23U2VE9E)

We currently support deployment to [Cloudflare Workers](./docs/deployment/workers.md) (recommended) and [Cloudflare Pages](./docs/deployment/pages.md).

## ⚒️ Configuration

[Configuration Docs](./docs/configuration.md)

## 🔌 API

[API Docs](./docs/api.md)

## 🤖 AI Skills

Install Sink AI Skills for enhanced coding assistance:

```bash
npx skills add miantiao-me/sink
```

## 🧰 MCP

We currently do not support native MCP Server, but we have OpenAPI documentation, and you can use the following method to support MCP.

> Replace the domain name in `OPENAPI_SPEC_URL` with your own domain name.
>
> The `API_KEY` is the same as the `NUXT_SITE_TOKEN` in the environment variables.

```json
{
  "mcpServers": {
    "sink": {
      "command": "uvx",
      "args": [
        "mcp-openapi-proxy"
      ],
      "env": {
        "OPENAPI_SPEC_URL": "https://sink.cool/_docs/openapi.json",
        "API_KEY": "SinkCool",
        "TOOL_WHITELIST": "/api/link"
      }
    }
  }
}
```

## 🙋🏻 FAQs

[FAQs](./docs/faqs.md)

## 💖 Credits

1. [**Cloudflare**](https://www.cloudflare.com/)
2. [**NuxtHub**](https://hub.nuxt.com/)
3. [**Astroship**](https://astroship.web3templates.com/)
4. [**Tailark**](https://tailark.com/)

## ☕ Sponsor

1. [Follow Me on X(Twitter)](https://404.li/x).
2. [Become a sponsor to on GitHub](https://github.com/sponsors/miantiao-me).
