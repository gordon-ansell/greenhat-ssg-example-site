---
name: Home
_layout: home
isHomePage: true
paginate:
    data: articles.type.post.desc()
    alias: posts
    perPage: 30
    dummy: homePlus.html
menus:
    top:
        url: /
        pos: 1
---