---
comments: true
date: 2014-02-01 9:30:00
layout: post
slug: welcome-to-my-blog
title: "Welcome to my blog"
summary: "Here is where I'll be talking about my course work, what I discover and what has me stumped. "
image: 'welcome-to-my-blog/tealeaf.jpg'
tags:
- ruby
- tealeaf
---
This is the first post to my [Tealeaf Training] [1] blog.  I'm trying to use GitHub User Pages 
and a Jekyll template for my blog.  So far it's been way too much work. I think I should have 
just used WordPress or Tumblr.

I thought all I would need to know was markdown but its lots of HTML/CSS and Javascript.
I'm just not a Web developer... yet. 
Please excuse the broken links while I figure out what I'm doing.

#####  Playing around with Markdown 

{% highlight ruby %}
def print_cards cards
  puts "#{cards.count}-card deck"
  cards.each do | rank, suit |
    puts "  #{rank} of #{suit}"
  end
end
{% endhighlight %}

[1]: http://www.gotealeaf.com "Introduction to Ruby and Web Development"
