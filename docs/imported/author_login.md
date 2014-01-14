---
layout: docs
title: author_login
prev_section: imported/author
next_section: imported/author_email
permalink: /docs/imported/author_login/
---

[The WordPress Jekyll importer](https://github.com/jekyll/jekyll-import/blob/0899f6b7a834f931bf495d3022f8b0d442412165/lib/jekyll-import/importers/wordpress.rb#L122) will save information about the original post author.

{% highlight yaml %}
---
author_login: john.smith
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
