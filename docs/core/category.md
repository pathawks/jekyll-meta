---
layout: docs
title: categories
prev_section: core/published
next_section: core/tags
permalink: /docs/core/category/
---

Instead of placing posts inside of folders, you can specify one or more categories that the post belongs to. When the site is generated the post will act as though it had been set with these categories normally. Categories (plural key) can be specified as a [YAML list](http://en.wikipedia.org/wiki/YAML#Lists) or a space-separated string.

{% highlight yaml %}
---
categories: [docs, core]
---
{% endhighlight %}