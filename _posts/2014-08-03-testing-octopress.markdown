---
layout: post
title: "Testing Octopress"
date: 2014-08-03T13:21:58+07:00
---

This is a test for octopress.
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores, officia, eligendi quasi nobis velit deserunt fuga eveniet fugiat. Libero, labore doloribus molestias quibusdam minus esse optio iure officiis sapiente velit.

{{ excerpt.separator }}

# Big title (h1)
==============

# Heading 1 #

## Heading 2 ##

Lorem ipsum dolor sit amet, consectetur adipisicing elit.

 Reiciendis, iste, temporibus, officiis suscipit vero aliquam cumque voluptatibus numquam ullam cupiditate ipsam optio excepturi autem molestiae distinctio quod saepe assumenda commodi!

> Blockquotes here.
> Lets try 2 lines.

How about bold text? **Here it is**

And how about italics? _This is it_


* This is a list
* second item
* **bolded item**
* _emphasized item_



{% highlight css %}
html, body{
	width:100%;	
}
{% endhighlight %}


{% highlight js %}
var s = "Testing javascript";
console.log(s);
{% endhighlight %}


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Let's test out a link

[A link](http://google.com)

A link with title

[A link with title](http://google.com "This is google website")