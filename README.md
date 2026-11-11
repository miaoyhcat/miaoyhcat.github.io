# miaoyhcat.github.io

Short entry point for the manga-to-pdf deployment: **https://miaoyhcat.github.io/**

This repository only hosts a redirect. The application itself runs on a private host and is
published through a Cloudflare tunnel; the target address changes on restart, so this page
resolves it at load time instead of hard-coding it.

- index.html — launcher (GitHub API -> current.txt -> fallback)
- current.txt — current tunnel address, updated automatically

Project: [manga-to-pdf](https://github.com/miaoyhcat/manga-to-pdf)

Personal use, non-commercial. Please support the official releases.
