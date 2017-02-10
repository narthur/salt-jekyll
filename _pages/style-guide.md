---
layout: page
title: Style Guide
permalink: /style-guide/
hidden: true
---

Hello, world

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

# Resources

- [Style Guide Boilerplate](http://bjankord.github.io/Style-Guide-Boilerplate/)

# The Style Guide

{% capture includeGuts %}
{% include component/index.html %}
{% endcapture %}
{{ includeGuts | replace: '    ', ''}}
