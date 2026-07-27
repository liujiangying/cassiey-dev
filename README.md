# cassiey.dev

Cassiey 的个人博客，使用 Hugo 构建并部署至 Cloudflare Pages。

## 本地预览

```bash
hugo server -D
```

## 构建

```bash
hugo --gc --minify
```

Cloudflare Pages 配置：

- Build command: `hugo --gc --minify`
- Build output directory: `public`
- Environment variable: `HUGO_VERSION=0.164.0`
