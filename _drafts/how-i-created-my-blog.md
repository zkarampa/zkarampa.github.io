---
title: How I created my blog
categories:
- Software Development
tags:
- jekyll
- blog
---

Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization site.

{% highlight shell %}
bundle exec jekyll serve help

bundle exec jekyll draft "How I created my blog"

bundle exec jekyll serve --draft -o

bundle exec jekyll publish _drafts/how-i-created-my-blog.md
{% endhighlight %}


https://github.com/jekyll/jekyll-compose
