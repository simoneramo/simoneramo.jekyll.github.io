---
layout: post
title:  "Another Article"
date:   2013-03-10 11:42:02
categories: wordpress
permalink: wordpress-restrict-access-plugin
---
Introducing [Restrict Lite](https://wordpress.org/plugins/restrict-lite/), this is a lightweight simple to use WordPress plugin to help you limit areas of posts/pages for with a simple short code. 

The plugin use’s [capabilities](http://codex.wordpress.org/Roles_and_Capabilities) and roles to manage if the content will be displayed.

Using the shortcode restrict and the arguments capability=”” roles=””, we can quickly lock out areas of a post directly from the WYSIWYG.
{% highlight html %}
	[ restrict capability="read" ] This text would show only to users that have permission to read [ /restrict ]
{% endhighlight %}

Check it out [here](https://wordpress.org/plugins/restrict-lite/), leave a comment or request if you would like any additional features!