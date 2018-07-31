---
layout: post
title: Darling, Dearest, Darcy
category: articles
tags: pop-culture
---

## The Problem

blue is the best, like the best, like really, really really 

fefewfewfew cewcewcew
## The Solution

I know this can be tricky and more verbose than uploading your Jekyll site directly to your repository. However GitHub Pages support static HTML pages, a workaround solution for using Almace Scaffolding on GitHub Pages is treating your Jekyll site as static pages:

- Build your site locally (`grunt build`).
- Upload Jekyll generated static files to your `username.github.io` repository.

If you'd like to keep all things under Git control, you can try the following file structure:

```
├── _amsf/ (Almace Scaffolding source code)
├── *.html (Jekyll-generated static pages)
└── README.md (your own readme)
```

