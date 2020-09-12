---
layout: page
title: About
---

<section class="posts">
<ul>
{% for post in site.posts %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%m-%d-%Y" }}</time></li>
{% endfor %}
</ul>
</section>


Sidey is a simple and minimalistic jekyll blogging theme.

### Features

- Responsive design
- Inline CSS
- Anchor headings
- Search
- Tags & tag pages
- Security headers (for Netlify hosting)
- 404 page
- Compressed CSS and HTML
- 100/100 score on Lighthouse, Page Speed Insights & Webpagetest
- Robots.txt
- Atom & Json feeds
- Sass
- Seo optimized (Twitter cards, Facebook Open Graph, Schema.org)
- Ultra fast (Only ~5kb of CSS)
- Sidebar navigation

### Screenshot

![Screenshot](screenshot.png)
