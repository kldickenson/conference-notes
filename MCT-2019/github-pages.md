# GitHub Pages - Mike Cole @colemike

[sample site](https://github-pages-demo.info/)

[Mike's demo repo](https://github.com/github-pages-demo/github-pages-demo.github.io)

Jekyll running in safe mode

Hosted in GitHub for free

Content is in GitHub repo

"github.io" URL but can do custom URL

## Jekyll

- static site generator
- runs on Ruby
- content is Markdown or HTML in folder structure
- Jekyll generates a website of purely static sites
- Sass right out of the box
- plugin library (custom/3rd party plugins not allowed on GitHub)
- themes
- can use task runner (i.e. Gulp)

## Pluses

- free SSL certificate via GitHub
- runs behind a CDN
- world class infrastructure
- all static content on server side, easily transferable

## _config.yml

## Front Matter
`
---
layout: template name
title:
permalink:
publish: true/false
date:
tags:
---
`
## layouts and includes

_layouts subfolder

layouts contain front matter as well

you can nest layouts

includes live in _includes folder

## Command Line

jekyll build

jekyll server (localhost server)

--livereload

--safe (disables 3rd party plugins)

## CNAME

file on line line with custom URL

## Third Party Tools

- [comments](disqus.com)
- [forms](formspree.io)
- [other?](snipcart.com)

## Limits

Repo size: 1GB

Bandwith: 100 GB/month

Builds: 10/hr

## imports
[importing](imports.jekyll.com)

## Liquid templating language

## Drawbacks
- no post scheduling
- no storage of large binary files

