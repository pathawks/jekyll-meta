---
layout: docs
title: author_url
prev_section: imported/slug
permalink: /docs/imported/author_url/
---

[The WordPress Jekyll importer](https://github.com/jekyll/jekyll-import/blob/0899f6b7a834f931bf495d3022f8b0d442412165/lib/jekyll-import/importers/wordpress.rb#L124) will save information about the original post author.

{% highlight yaml %}
---
author_url: http://example.com/john.smith
---
{% endhighlight %}

<div class="note warning">
  <h5>Inconsistant Behavior</h5>
  <p>Other importers use a more YAMLly way of importing author information.</p>
</div>

{% highlight yaml %}
---
author: 
    name: "John Smith"
    url: "http://example.com/john-smith"
    image: "http://example.com/john-smith.png"
---
{% endhighlight %}
