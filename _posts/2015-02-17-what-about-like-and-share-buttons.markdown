---
title: What about like and share buttons?
subtitle: Startup questions
layout: blog
modal-id: 2
date: 2015-02-17
img: ic_group_add_grey600_48dp.png
---

You have to start exposing your startup web site to social media as early as possible. The easiest way to engage users is to add social buttons such as Facebook Like, Google+ share, and LinkedIn widgets. I posted another [article for adding simple buttons](http://dmitriyev.name/fb-g-buttons/) to your Wordpress site. That article was mostly for social media class students I am teaching. This one is specific for startups and their first web sites. 

&nbsp;  

##### First, let's review types of Facebook buttons:

&nbsp;  

###### 1. Facebook Share button, 

It's pretty obvious - share this post on the Facebook page of a visitor of this site:

<iframe src="//www.facebook.com/plugins/share_button.php?href=http%3A%2F%2Fyourmvp.consulting%2Fblog%2Fwhat-about-like-and-share-buttons%2F&amp;layout=button&amp;appId=369264396586885" scrolling="no" frameborder="0" style="border:none; overflow:hidden;" allowTransparency="true"></iframe>

###### 2. Facebook Like button

similar to a share button, it will share this post on Facebook timeline of a visitor's Facebook page. Unlike in case of sharing, the visitor doesn't have a chance to add a comment.

<iframe src="//www.facebook.com/plugins/like.php?href=http%3A%2F%2Fyourmvp.consulting%2Fblog%2Fwhat-about-like-and-share-buttons%2F&amp;width&amp;layout=button&amp;action=like&amp;show_faces=false&amp;share=false&amp;height=35&amp;appId=369264396586885" scrolling="no" frameborder="0" style="border:none; overflow:hidden; height:35px;" allowTransparency="true"></iframe>

&nbsp;  
&nbsp;    

###### 3. Facebook Follow button

this one will let visitor of this site to follow the author of this site

<iframe src="//www.facebook.com/plugins/follow.php?href=https%3A%2F%2Fwww.facebook.com%2Fdmitriyev&amp;width=100&amp;height=35&amp;colorscheme=light&amp;layout=button&amp;show_faces=false&amp;appId=369264396586885" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:100px; height:35px;" allowTransparency="true"></iframe>

&nbsp;  
&nbsp;  


##### Review Google+ buttons

&nbsp;  


###### 1. Share post

<div class="g-plus" data-action="share" data-annotation="none" data-height="24" data-href="http://yourmvp.consulting/blog/what-about-like-and-share-buttons/"></div>

&nbsp;  
&nbsp;  


###### 2. Add +1

<div class="g-plusone" data-annotation="none" data-href="http://yourmvp.consulting/blog/what-about-like-and-share-buttons/"></div>

&nbsp;  
&nbsp;  


###### 3. Folow

<div class="g-follow" data-annotation="none" data-height="24" data-href="//plus.google.com/u/0/103226308480698085474" data-rel="author"></div>

&nbsp;  
&nbsp;  

##### Step-by-step instructions for adding FB buttons to your site

This guide assume that you want to add buttons to static HTML site that is created manually, using Jekyll, or simialr mechanism. Most of it would work in Wordpress too, but that's not the focus of this article.

&nbsp;  

###### 1. Create and publish a FB application

Go to [https://developers.facebook.com](https://developers.facebook.com), and select My Apps -> Add a New App menu, then select Website button:

<a href="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-12.49.58-PM.png"><img class="alignnone wp-image-82 size-medium" src="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-12.49.58-PM-300x200.png" alt="Screen Shot 2015-01-31 at 12.49.58 PM" width="300" height="200" /></a>

Enter app name "My blog test" and Create New Facebook App ID, then confirm your entry and Skip Quick Start when it shows up. It should look like this:

<a href="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.15.48-PM.png"><img class="alignnone wp-image-83 size-medium" src="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.15.48-PM-300x151.png" alt="Screen Shot 2015-01-31 at 1.15.48 PM" width="300" height="151" /></a>
 

Click on Settings menu on the left side and fill out the Contact Email field. The save changes and go to Status & Review menu item. There is a switch next to "Do you want to make this app and all its live features available to the general public?" text, it says NO. You should be able to click it and change to YES. You application should be published, and you should see this screen:

<a href="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.34.40-PM.png"><img class="alignnone size-medium wp-image-84" src="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.34.40-PM-300x94.png" alt="Screen Shot 2015-01-31 at 1.34.40 PM" width="300" height="94" /></a>
 
&nbsp;  

*IMPORTANT:*  if there is no solid green circle next to the name of the app, it's not published

&nbsp;  

###### 2. Generate FB Share & Like buttons and add to your blog

All buttons can be generated from this page: [https://developers.facebook.com/docs/plugins](https://developers.facebook.com/docs/plugins)

You will need a working link to your blog post before generating buttons code. If you don't publish your blog post before generating a button, Facebook may cache error 404 - page not found, and it will take time or additional steps to resolve it. That's why you should create a new blog post. Then publish it, and copy its URL. Go back to the Facebook Social Plugins page. Choose the Like button first, and paste your Blog post URL into "URL to like" field. It will look like this:

<a href="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.45.37-PM.png"><img class="alignnone size-medium wp-image-86" src="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.45.37-PM-300x185.png" alt="Screen Shot 2015-01-31 at 1.45.37 PM" width="300" height="185" /></a>

Click on Get Code and select IFRAME tab. It will look like this:

<a href="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.47.03-PM.png"><img class="alignnone size-medium wp-image-87" src="http://dmitriyev.name/wp-content/uploads/2015/01/Screen-Shot-2015-01-31-at-1.47.03-PM-300x165.png" alt="Screen Shot 2015-01-31 at 1.47.03 PM" width="300" height="165" /></a>

Copy that code and paste to your page now. If you are using Jekyll, you are probably using Markdown format for your blog posts. The IFRAME code works just fine if it's inserted "as is"

Now, publish/update that page. When you view your blog page, the buttons should be visible and you should be able to like and share your blog post on FB.

&nbsp;  
&nbsp;  

###### 3. Generate FB Follow button

The follow button can be generated here: [https://developers.facebook.com/docs/plugins/follow-button](https://developers.facebook.com/docs/plugins/follow-button)

Just fill out the Profile URL with a link to your own FB profile, such as https://www.facebook.com/dmitriyev. Then follow the same step as for Like/Share buttons and get the code for IFRAME. Then insert it into your blog. It's probably better to add Follow button to a static home or about page of your blog, but it's okay if it shows up in each blog post too.

IMPORTANT: if you get Error "Following is not enabled for ..." viewing your page, it most likely means that your FB privacy setting don't allow to view your public posts. You can change it as described here: [https://www.facebook.com/help/201148673283205/](https://www.facebook.com/help/201148673283205/)
 
&nbsp;  
&nbsp;  

##### Step-by-step instructions for adding G+ buttons to your Wordpress site

&nbsp;  

###### 1. Generate G+ Share & +1 buttons and add to your blog

The G+ Share buttons can be generated using these links:

[https://developers.google.com/+/web/share/](https://developers.google.com/+/web/share/)

[https://developers.google.com/+/web/+1button/](https://developers.google.com/+/web/+1button/)

It pretty easy to do. Just like in case with FB, you should paste the URL to your blog post into "URL to share" field, and you should see code that looks like this:

```<div class="g-plus" data-action="share" data-annotation="none" data-height="24" data-href="http://yourmvp.consulting/blog/what-about-like-and-share-buttons/"></div>```

As you can see, this code needs to be placed in two different places. You need to customize your Jakyll header template in order to add a script tag to the right place. As a reminder, you can find the full source code for this blog here: [https://github.com/admitriyev/agency-jekyll-theme](https://github.com/admitriyev/agency-jekyll-theme)

```<!-- Place this tag in your head or just before your close body tag. -->
<script src="https://apis.google.com/js/platform.js" async defer></script>```

Update your post, and see if it works now.

&nbsp;  

###### 2. Generate G+ Follow button

The G+ follow button is very similar to G+ Share and +1 buttons. You just need to specify what profile you would like the users to follow. Use this link, and follow the same instructions as for G+ share button above:

[https://developers.google.com/+/web/follow/](https://developers.google.com/+/web/follow/)


Done! Make sure to test it all now. 
