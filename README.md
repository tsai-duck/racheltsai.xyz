# [racheltsai.xyz](https://racheltsai.xyz/)

## 🛠️ start dev server

```
hugo server --buildDrafts
// or
hugo server -D
```

## ✏️ add content

1. add a new page

```
hugo new content posts/hello-world.md
```

2. set the front matter `draft` parameter to `false`

```
+++
title = 'My First Post'
date = 2024-01-14T07:07:07+01:00
draft = false
+++
```

## 🚀 publish site and deploy

simply push to github. Cloudflare will take care of the rest.

## 🔗 useful links

- [Deploy a Hugo Site w/ Cloudflare](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/)
- [Hugo Docs](https://gohugo.io/documentation/)
- [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
