---
comments: true
date: 2014-02-10 22:30:00
layout: post
slug: start-of-week-two
title: "Start of week two"
image: 'tealeaf.jpg'
tags:
- tealeaf
---
This week I'm working on my object oriented Blackjack game.
My procedural version was a good starting point, I just needed to encapsulate the behavior into classes.
I started with a Card class and a Deck class.  I decided to go with a Hand class instead of seperate Player and Dealer classes.
My main game code went into a Blackjack class.  I creaded test for each class to make sure the behavior is correct while I refactored the code.
I think the encapsulation works OK and my methods are farily small but there's always room for improvement.

The biggest problem I had/have is trying to use command line arguments with rspec.  Seems like
OptionParser does not work well with rspec.  I like the nested format option with rspec and had to add that to my code
to keep rspec happy.  I'm hoping there is a better solution.

Let me know what you think.  The code is in my Introduction to Ruby and Web Development Project under week-2 and
can be found [here][code].

[code]: http://github.com/mark-greene/intro-ruby-web/tree/master/week-2
