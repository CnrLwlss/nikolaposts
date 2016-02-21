<!-- 
.. title: Markdown article
.. slug: markdown-article
.. date: 2016-02-14 13:48:52 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Testing Markdown
================

One of the nice things about [Nikola](https://getnikola.com/) is that you have several different markup options for writing your articles.  This article is written using [Markdown](https://daringfireball.net/projects/markdown/basics).

It's possible to write code:

	:::R
	# Logistic growth model #
	logist<-function(K,r,g,t) (K*g*exp(r*t))/(K+g*(exp(r*t)-1))

	# Generalised logistic growth model #
	# Solution of dx/dt = r*x*(1-(x/K)^v)
	Glogist<-function(K,r,g,v,t) K/(1+(-1+(K/g)^v)*exp(-r*v*t))^(1/v)

I'm not sure how to write math with [MathJax](https://www.mathjax.org/).
