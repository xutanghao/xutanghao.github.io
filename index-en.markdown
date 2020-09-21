---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit 's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
#title: Xutanghao Blog
#title: Xu Tanghao's Blog
title: Welcome to Xu Tanghao's Blog
permalink: /index.html
header:
  image: /assets/img/home-header.jpg
tagline: > # this means to ignore newlines until "repository:"
  Write an awesome description for your new site here. You can edit this
  line in index.md. It will appear in your document head meta (for
  SEO optimization) and in your feed.xml site description.
excerpt: >
  no use for the excerpt 2020-07-25.
repository:
  is_project_page: true
  show_downloads: true
ref: home
lang: en
---

Simple Blog Theme is a clean, responsive blogging theme for Jekyll. It is inspired by the Cayman Blog Theme.

This theme has all you need to start today blogging with Jekyll, and no effort: pages, posts, few social buttons. Try loading this on mobile too.

Have a look at the Github page for more information.

You find this descriptive text in the `index.md` file, so you can change it, or remove it completely, according to your needs.

<h1>Latest Projects</h1>
<div>&nbsp;</div>
{% include list-category-posts.html lang=page.lang category="projects" max_posts=3 max_post_tags=3 %}
