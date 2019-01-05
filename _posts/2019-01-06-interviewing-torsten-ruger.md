---
layout: post
title: Interview - Torsten Ruger
subtitle: Speaking at Rubyconf India 2019 on RubyX
date: 2019-01-06
author: Satish Manohar Talim
---

{% include image.html
           img="/img/interviews/torsten-ruger.jpg"
           url="https://medium.com/@rubydesign"
           title="Torsten Ruger"
           class="circular"
           %}

It's my priviledge to present you today the discussion I had with [Torsten](https://medium.com/@rubydesign) who has nearly four decades of coding experience.

### About Speaker

Torsten Ruger has been coding in various roles for ~38 years. He found <b><i>Ruby</i></b> in 2001, and hasn’t coded much else since. Nowadays, he feels privileged because he can code for fun, and what interests him most is how code actually works. Hence the very self referential implementation of ruby in ruby.

He is going to speak about <b><i>RubyX, compiling ruby to binary</i></b>.<br>
When he doesn’t code he does timber-framing and builds houses. He lives in the finnish nature, with his wife, where they run a B&B, and enjoy the quiet life.

### Interview

Me >> <b><i>Welcome Torsten and thanks for taking out time to share your thoughts.
For the benefit of the readers of this blog could you please introduce yourself and tell us what you do for a living?</i></b>

<b>Torsten >></b> My name is Torsten Ruger(50), I live with my wife in the finnish countryside. After studying <u>Physics</u>, I ended up in Computing and started writing Web Applications in 1996. I worked in various companies mostly programming the web, until we opened our B&B in 2006. After that, I have mostly done freelance work with `Rails`. I also enjoyed teaching some boot-camp classes in recent years.<br>
My hobby for many years was <b><i>Woodwork</i></b>, but recently the roles have swapped and I program as a hobby and run a timber-frame-house company.

Me >> <b><i>It's so great to know that open source excites you so much. I am glad to know that your projects have been an interesting demonstration of Ruby/Rails. Do you have any advice for a student or beginners getting into open source?</i></b>

<b>Torsten >></b> Think of project maintainers as just normal people. They have more experience, yes, but at some point started out just like you.<br>
Choose a project that really captures your interest and start contributing with small things. Also get your company to contribute if they use open source, and you can even choose your employer by how they contribute to open source.

Me >> <b><i>That's really nice Torsten. I am glad to see the recent rise in Open source culture in India and hopefully, if this trend goes on then we all would learn a lot from this. Can you tell us a bit about your projects in Ruby/Rails?</i></b>

<b>Torsten >></b> I am currently writing a compiler [RubyX](https://github.com/ruby-x/rubyx), that compiles ruby to binary code. While this will speed up ruby, it will also move the ruby runtime in reach of the normal ruby programmer, as it is written in ruby. I think it is important for a programmer to choose and own his tools, much like any craftsman really.<br>
For me, we are still a long way from the ideal way of programming, but since learning about `Smalltalk` in the early 90's, I've been of the opinion that `Object Oriented Programming` is the most natural way for a human to look at processes. I hope my efforts will encourage more object oriented programming, and especially help ruby to spread into more areas.<br>
In the past, I have also written a small POS/e-commerce project and way back an in-memory gc'd database. But neither really received any attention.

Me >> <b><i>That’s cool Torsten, your projects are interesting. So when did you start working on Ruby/Rails and why?
</i></b>

<b>Torsten >></b> I started programming `Ruby`, the moment I found it, this was in 2001. I used it initially to test the apps; we were still writing in Java. Ruby is really great for testing and has only got better.<br>
I started using Rails in 2006, as it encaptured all best practices at the time in a nice package, and added a few new ones. Seeing it grow into the large, mature and well written framework that it is (and has been mainly after 3.0) has been a great joy. Apart from being a category leading piece of software, I think it is the most successful open source project that I know.

Me >> <b><i>How excited are you about RubyConfIndia?</i></b>

<b>Torsten >></b> I am very happy to return to RubyConf India. I visited with my wife in 2016 and we really enjoyed the atmosphere and people.

Me >> <b><i>Do you have any other suggestions for our readers?</i></b>

<b>Torsten >></b> I would suggest young programmers to take an active role in the open source community, don't just be consumers, but participants.<br>
Also, I hear many people say they like Ruby a lot; but it is not that enough and so they have to use something else. A prime example of this is, Rubyists doing JS they don't like, instead of using opal. I think one should stand up for what one enjoys and not just go the easy way.

### Related links

- [RubyX](https://github.com/ruby-x/rubyx){:target="_blank"}
- [Understanding RubyX though historic decisions](https://medium.com/ruby-x/understanding-rubyx-though-historic-decisions-18a5982a8dce){:target="_blank"}
