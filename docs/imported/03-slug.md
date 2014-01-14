---
layout: docs
title: slug
prev_section: imported/type
next_section: imported/comment_count
permalink: /docs/imported/slug/
---

[The WordPress Jekyll importer](https://github.com/jekyll/jekyll-import/blob/0899f6b7a834f931bf495d3022f8b0d442412165/lib/jekyll-import/importers/wordpress.rb#L116) will save a posts original globally unique identifier to the front matter of the imported post.

It is important to preserve this ID in Feeds, to avoid having swaths of old posts presented to readers as new.

{% highlight yaml %}
---
slug: example_post
---
{% endhighlight %}