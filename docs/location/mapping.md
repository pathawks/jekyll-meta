---
layout: docs
title: mapping
prev_section: location/location
permalink: /docs/location/mapping/
---

[jekyll-mapping](https://github.com/matthewowen/jekyll-mapping#basic-usage) will display a map if a post has been geotagged.

It uses it's own system of saving a geotag to a post.

{% highlight yaml %}
---
mapping:
    title: "Random Office Building"
    latitude: "37.78208"
    longitude: "-122.391241"
    link: /some/awesome/path
---
{% endhighlight %}