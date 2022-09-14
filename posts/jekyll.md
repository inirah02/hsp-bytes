---
title: "Github pages & Jekyll"
description: All about deploying using github pages and jekyll 
date: 2021-08-05
tags: 
    - howto
layout: layouts/post.njk
---

Jekyll is a static site generator with built-in support for GitHub Pages. Jekyll takes Markdown and HTML files and creates a complete static website based on your choice of layouts. Jekyll supports Markdown and Liquid, a templating language that loads dynamic content on your site.

Configuring Jekyll in your GitHub Pages site:

You can configure most Jekyll settings, such as your site's theme and plugins, by editing your *_config.yml* file.

Front Matter:

To set variables and metadata, such as a title and layout, for a page or post on your site, you can add YAML front matter to the top of any Markdown or HTML file.

Themes:

You can add a Jekyll theme to your GitHub Pages site to customize the look and feel of your site.

Plugins:

You can download or create Jekyll plugins to extend the functionality of Jekyll for your site. For example, the [jemoji](https://github.com/jekyll/jemoji) plugin lets you use GitHub-flavored emoji in any page on your site the same way you would on GitHub.

Syntax Highlighting:

To make your site easier to read, code snippets are highlighted on GitHub Pages sites the same way they're highlighted on GitHub.

Building Site Locally:

If you are publishing from a branch, changes to your site are published automatically when the changes are merged into your site's publishing source. If you are publishing from a custom GitHub Actions workflow, changes are published whenever your workflow is triggered (typically by a push to the default branch). If you want to preview your changes first, you can make the changes locally instead of on GitHub. Then, test your site locally.
