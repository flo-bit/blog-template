---
title: "Minimal setup with github pages"
description: "Learn how to use this blog template with github actions"
pubDate: "Oct 26 2024"
published: true
heroImage: "/src/assets/blog-placeholder-2.jpg"
tags: ["setup"]
---

1. Fork [the repository of this blog](https://github.com/flo-bit/blog-template)

2. Set up your blog info in `src/config.json` (most importantly set `SITE` and `BASE` to your corresponding values, see [`src/consts.ts`](../const-ts) for more info)

3. Add your blog posts in `src/content/blog/` (see [adding content](../adding-content) for more info)

4. Add your info in `src/content/info/`:

- `description.md` is used for the homepage description
- `about.md` is used for the about page

5. In your repository settings, set up github pages to deploy using github actions

6. Enjoy your new blog at: `https://<your-github-username>.github.io/<your-repo-name>`

For more information on how you can add content see the post about [adding content](../adding-content) or read about [supported markdown features here](../markdown-style-guide).