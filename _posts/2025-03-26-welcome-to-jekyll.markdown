---
layout: post
title:  "Hello"
date:   2025-03-26 20:15:26 +0100
categories: rust 
---
This my first post. I hope it will not be too boring.
{% highlight rust %}
fn _2d(index:usize,n:usize) -> (usize,usize) {
	assert!(index<(n*n));
	let x=index%n;
	let y=index/n;
	(x,y)
}
{% endhighlight %}

[test](https://github.com/julien5)

