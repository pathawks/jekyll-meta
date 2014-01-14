---
layout: docs
title: author
prev_section: imported/comment_count
next_section: imported/author_login
permalink: /docs/imported/author/
---

[The WordPress Jekyll importer](https://github.com/jekyll/jekyll-import/blob/0899f6b7a834f931bf495d3022f8b0d442412165/lib/jekyll-import/importers/wordpress.rb#L121) will save information about the original post author.

In this instance, `author` is a simple string with the author's full name.

{% highlight yaml %}
---
author: John Smith
---
{% endhighlight %}

<div class="note warning">
  <h5>Inconsistant Behavior</h5>
  <p><a href='https://github.com/coolaj86/blogger2jekyll/blob/344f8ef4cdfab56fad5b02b9d0f3020f839938ef/lib/index.js#L108'>Other importers</a> use a more YAMLly way of importing author information.</p>
</div>

{% highlight yaml %}
---
author: 
    name: "John Smith"
    url: "http://example.com/john-smith"
    image: "http://example.com/john-smith.png"
---
{% endhighlight %}
