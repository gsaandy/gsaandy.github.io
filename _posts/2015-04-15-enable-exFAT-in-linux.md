---
layout: post
title: "Linux - Enable exFAT"
comments: false
description: "How to enable exFAT in Ubuntu"
keywords: "ubuntu, how to enable exFAT"
---

#### How to enable exFAT in Ubuntu

* Add Universe apt repository
{% highlight bash %}
sudo add-apt-repository universe
sudo apt-get update
{% endhighlight %}
* Install exfat-fuse exfat-utils
{% highlight bash %}
sudo apt-get install exfat-fuse exfat-utils
{% endhighlight %}
