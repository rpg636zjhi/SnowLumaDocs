# SnowLumaDocs

SnowLuma 文档站。基于 [Fumadocs](https://fumadocs.dev)（Next.js 16 + MDX）。

> [!WARNING]
> **本仓库仅为技术文档存档，不含任何程序本体、二进制、安装包或可运行代码。**
> 不提供下载、不提供部署指导、不提供技术支持，也不鼓励任何人使用相关软件。
> 文档内容可能已过时、不完整或与现状不符，**仅供参考与计算机历史研究**。
> 使用前请自行确认符合所在地法律法规及平台服务条款，**一切后果由使用者自行承担**。

## 本地开发

```bash
pnpm install
pnpm dev
```

打开 http://localhost:3000

## 构建

```bash
pnpm build
pnpm start
```

## 内容位置

文档源文件位于 `content/docs/`，按 `meta.json` 中的顺序在侧边栏排列。新增页面时同步更新 `meta.json` 即可。

## 技术栈

- Next.js 16 (App Router)
- Fumadocs Core / UI / MDX
- React 19
- Tailwind CSS 4
- TypeScript
