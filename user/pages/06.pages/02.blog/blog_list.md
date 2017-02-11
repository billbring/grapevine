---
title: 'Blog Page'
blog_url: blog
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true
    show_date: 0
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

