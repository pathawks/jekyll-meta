---
layout: docs
title: comment_count
prev_section: imported/slug
next_section: imported/author
permalink: /docs/imported/comment_count/
---

[The WordPress Jekyll importer](https://github.com/jekyll/jekyll-import/blob/0899f6b7a834f931bf495d3022f8b0d442412165/lib/jekyll-import/importers/wordpress.rb#L120) will save the number of comments associated with a post in the front matter of the imported post.

{% highlight yaml %}
---
comment_count: 12
---
{% endhighlight %}