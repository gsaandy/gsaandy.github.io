---
layout: post
title: "Mac - Show hidden files"
comments: false
description: "How to show hidden files in mac"
keywords: "mac, macos, how to show hidden files, hide hidden files"
---

#### How to install Homebrew

Add the following snippet to ~/.bash_profile
{% highlight bash %}
alias show_files="defaults write com.apple.finder AppleShowAllFiles YES; killall Finder /System/Library/CoreServices/Finder.app"
alias hide_files="defaults write com.apple.finder AppleShowAllFiles NO; killall Finder /System/Library/CoreServices/Finder.app"
{% endhighlight %}

* Restart the terminal
* To show the hidden file
  *show_files
* To hide files
  *hide_files
