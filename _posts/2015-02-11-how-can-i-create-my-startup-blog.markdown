---
title: How can I create my startup blog?
subtitle: Startup questions
layout: blog
modal-id: 2
date: 2015-02-13
img: blog-icon-black-300.png
---

As Ara T. Howard pointed out in his blog post, [Static is the New Black](http://dojo4.com/blog/static-is-the-new-black "Blog post")  . Startups need to establish their web presence as soon as possible. It’s a good idea to register a domain, get a few variations of the name to get more traffic, and point all of them to your landing page. There are many ways to build that landing page. There are pretty good services that you can use to make your first one, there is also Wordpress that I discussed in my previous blog post (URL). There are also trade-offs for every approach. Do you really need a full CMS system for a simple thing like that? 

Remember that your goals are probably:

* to have something to put on your business card, and point people who want more information about your startup
* to drive traffic to your web site, and convert visitors to users
* to get beta users, or subscribers to your newsletter

I tried several approaches myself. I used Wordpress, then turned 180 degrees and did everything manually by hand. It felt great: manually created pages, complete flexibility, sweet freedom! Well... almost. If you create a few pages, a dozen of blog posts, and then decide to add a new tracking feature or change the layout consistently, it means you will do a lot of searching-replacing in your HTML files, and make some bad mistakes. I realized I did not like that side of the spectrum either. I decided to go for something in the middle, which is called Jekyll. It’s a tool that provides a framework for creating a basic structure, layouts, styles, and simple features like Google analytics for your web site. It’s not very complex, but it requires basic web development skills to setup. Once it’s setup and deployed, anyone else can add content as long as they know basic Markdown syntax and have some Github skills. What are the advantages of this approach? In my opinion, it’s still flexible, almost as flexible as a fully hand-crafted solution. It’s really fast, because there is no extra overhead processing PHP or other code on the server side. It’s better than a manual solution, because changes can be done in one template and applied to all pages generated using that template. 

I use Jekyll to host this web site. I forked a public Github repository with an open source theme as a starting point, and modified it to make it work for me. The code is fully available in this repository on Github [agency-jekyll-theme](https://github.com/admitriyev/agency-jekyll-theme). I will continue working on it, and exploring additional features. 