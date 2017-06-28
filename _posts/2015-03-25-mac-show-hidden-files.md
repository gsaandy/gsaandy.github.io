---
layout: post
title: "Mac - Show hidden files"
comments: false
description: "How to show hidden files in mac"
keywords: "mac, macos, how to show hidden files, hide hidden files"
---

#### How to show/hide hidden files in Mac

*Add the following snippet to `~/.bash_profile`
{% highlight bash %}
alias show_files="defaults write com.apple.finder AppleShowAllFiles YES; killall Finder /System/Library/CoreServices/Finder.app"
alias hide_files="defaults write com.apple.finder AppleShowAllFiles NO; killall Finder /System/Library/CoreServices/Finder.app"
{% endhighlight %}
* Reload the changes
{% highlight bash %}
source ~/.bash_profile
{% endhighlight %}
* To show the hidden file
{% highlight bash %}
show_files
{% endhighlight %}
* To hide files
{% highlight bash %}
hode_files
{% endhighlight %}

