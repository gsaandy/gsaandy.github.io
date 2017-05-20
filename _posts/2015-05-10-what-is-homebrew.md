---
layout: post
title: "Homebrew"
comments: false
description: "What is homebrew and how to install it"
keywords: "homebrew, mac, macos, how to install homebrew"
---
#### What is Homebrew
  * The missing package manager for macOS.
  * Homebrew made things easy to install packages/libraries(like maven, wget etc) in macOS in a single command.

#### How to install Homebrew

Paste the following ruby snippet in the mac terminal
{% highlight ruby %}
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
{% endhighlight %}

##### Check the installation
Following will show the version and git revision of homebrew.
{% highlight bash %}
brew -v
{% endhighlight %}

#### How to install a new package (say Maven)

  * Install maven using following command in terminal
{% highlight ruby %}
brew install maven
{% endhighlight %}  


#### How to Uninstall Homebrew

Paste the following ruby snippet in the mac terminal
{% highlight ruby %}
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"
{% endhighlight %}  
