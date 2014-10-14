---
layout: post
title:  "Hello World!"
date:   2014-10-01 14:34:25
categories: jekyll update
tags: featured
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.jpg
---
Hello! This is a test post just to try some things out. 

Jekyll also offers powerful support for code snippets:

	{% highlight ruby %}
	def print_hi(name)
	  puts "Hi, #{name}"
	end
	print_hi('Tom')
	#=> prints 'Hi, Tom' to STDOUT.
	{% endhighlight %}

LaTeX Test: $$\sum\limits_{j} w_j*x_j$$
	

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

{% highlight js %}

<footer class="site-footer">
<a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
<div class="inner">a
<section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; 2014 &bull; All rights reserved.</section>
<section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
</div>
</footer>
{% endhighlight %}


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
