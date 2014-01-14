---
layout: docs
title: location
next_section: location/mapping
permalink: /docs/location/location/
---

[blogger2jekyll](https://github.com/coolaj86/blogger2jekyll/blob/344f8ef4cdfab56fad5b02b9d0f3020f839938ef/lib/index.js#L117) will import geocordinates if a post has been geotagged.

{% highlight yaml %}
---
location:
    name: "Random Office Building"
    latitude: "37.78208"
    longitude: "-122.391241"
    box: [37.68208, -122.291241, 37.88208, -122.491241]
---
{% endhighlight %}