---
layout: post
title: "Accidental Deletion in Linux: First Line of Defense"
date: 2014-12-28T16:58:23-05:00
---

We've all [had a bad experience](https://www.youtube.com/watch?v=-9Q1xx7t-HU)
that we don't want to talk about, wherein we accidentally deleted or lost
important files. In college, I started using this as the first line of defence,
after I accidentally deleted two days of work immediately before a meeting with
my research advisor:

{% highlight bash %}
# use trash-cli (apt-get install trash-cli) to save deleted files in "recycle
bin"

alias rm='trash-put'
{% endhighlight %}

We owe this to our employers and customers, as well as ourselves. Re-doing work
is expensive and soul-sucking. And you **will** lose or accidentally delete
something at some point.

