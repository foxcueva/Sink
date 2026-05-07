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


## 🪧 演示（原作者提供）；

在 [Sink.Cool](https://sink.cool/dashboard) 体验演示。请使用下方的 Site Token 登录：

```txt
Site Token: SinkCool
```

<details>
  <summary><b>Screenshots</b></summary>
  <img alt="Analytics" src="./docs/images/sink.cool_dashboard.png"/>
  <img alt="Links" src="./docs/images/sink.cool_dashboard_links.png"/>
  <img alt="Link Analytics" src="./docs/images/sink.cool_dashboard_link_slug.png"/>
</details>

## 🧱 使用技术

- **框架**: [Nuxt](https://nuxt.com/)
- **数据库**: [Cloudflare Workers KV](https://developers.cloudflare.com/kv/)
- **分析引擎**: [Cloudflare Workers Analytics Engine](https://developers.cloudflare.com/analytics/)
- **UI 组件**: [shadcn-vue](https://www.shadcn-vue.com/)
- **样式:** [Tailwind CSS](https://tailwindcss.com/)
- **部署**: [Cloudflare](https://www.cloudflare.com/)

## 🚗 开发路线图 [进行中]

欢迎提交代码贡献和 PR。

- [x] 浏览器扩展程序 - [Sink Tool](https://github.com/zhuzhuyule/sink-extension)
- [x] Chrome 扩展程序 - [Sink Quick Shorten](https://chromewebstore.google.com/detail/sink-quick-shorten/emlojomjpenjgkaphajcokijobpkejih)
- [x] Raycast 扩展程序 - [Raycast-Sink](https://github.com/foru17/raycast-sink)
- [x] Apple 快捷指令 - [Sink Shortcuts](https://s.search1api.com/sink001)
- [x] iOS 客户端 - [Sink](https://apps.apple.com/app/id6745417598)
- [ ] 增强的链接管理（使用 Cloudflare D1）
- [ ] 数据分析增强（支持合并过滤条件）
- [ ] 控制台性能优化（无限滚动加载）
- [ ] 单元测试

## 🏗️ 部署

> 视频教程：[点击观看](https://www.youtube.com/watch?v=MkU23U2VE9E)

我们目前支持部署到 [Cloudflare Workers](./docs/deployment/workers.md)（推荐）和 [Cloudflare Pages](./docs/deployment/pages.md)。

## ⚒️ 配置

[配置文档](./docs/configuration.md)

## 🔌 API

[API 文档](./docs/api.md)

## 🤖 AI 技能

安装 Sink AI 技能以获得更强大的编码辅助：

```bash
npx skills add miantiao-me/sink



## 🧰 MCP


我们目前原生不支持 MCP Server，但我们提供了 OpenAPI 文档，您可以使用以下方式支持 MCP。
​请将 OPENAPI_SPEC_URL 中的域名替换为您自己的域名。​
API_KEY 与环境变量中的 NUXT_SITE_TOKEN 相同。

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
