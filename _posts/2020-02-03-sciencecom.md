---
layout: post
title: Ways to communicate science using Github
tags: 'Science communication Github websites'
thumbnail: "assets/img/portfolio/sci-comm.png"
color: rgb(128, 177, 179)
excerpt_separator: <!--more-->
published: true
---

A large part of science is communication. After all, if we can't explain the purpose of our research, then why should people support us? One way research can be made more accessible is by building websites that delineate the research objectives and allow ordinary people to learn about the research and perhaps implement it.
<!--more-->
For those of us whom are scientists but not necessarily computer scientists, a relatively simple way to do this by using Github.

* First choose a website theme on Github
* Fork or clone this website 
* adjust the _config.yml_ using your own Github account

**Sign up for Github**
Sign up here: [Github](https://github.com/)
**Choosing a theme**
Check out [these themes](https://jekyll-themes.com/free/) to find what works best for your site
**Fork the theme you like**
Go to your theme's Github page or repository
Choose Fork this repository. This repository should now show up on your Github page. Click "use as template" in order to make this your own repository. Choose a name.
**Adjust config file**
*Configure site*
open _config.yml_ file to adjust the url. If you want the website to be your github name, then add in your github name as the url and leave baseurl as "". 
>baseurl: ""

>url: "https://username.github.io"

Alternatively, if you want to add this as a subpath to your directory then the baseurl should be the name you want as the subpath:
>baseurl: "/sub-directory"

>url: "https://username.github.io/"

If you want to create a page completely independent of your user name then you should create a new organization, and then you can use the organization name as your website name.
>baseurl: ""

>url: "https://organization.github.io"

*Adjust metadata*
Change these variables in _config.yml:

>title: My Jekyll Blog                 # Name of website
avatar: assets/img/triangle.png       # Path of avatar image, to be displayed in the theme's header
description: My blog posts            # Short description, primarily used by search engines
favicon: assets/favicon.ico           # Icon displayed in the tab

*Customize Header and Footer*
Customize your site header/footer with these variables in _config.yml:

>header text: Welcome to my Jekyll blog
header feature image: assets/img/sample3.png
footer_text: Copyright 2017

**Customize your pages or posts**
If your theme is a blog theme, there should be a folder called '_posts_' or if you are customizing website pages they may be in a folder called '_pages_'.
In this folder or in the main folder you will find markdown files. Markdown is a type of file that creates an easy way to write texts or add pictures that can then be converted to html content. This is automatically converted by Github, so making a new page or blog post is easy. For more information on markdown click [here.](https://www.markdowntutorial.com/)

**Add images**
Images can be added by putting the address (or directions) to the folder that contains images. Often this folder is called _IMG_.
To direct a markdown page to an image:
> img src="../img/image.jpg" alt='alt name' height="350px"

**Your science will take off by using Github!**
Finally look through the website which you cloned and see how they did things.

![image of snowy owl]({{ "/assets/img/pexels/snowy-owl_robert_holden_immature.jpg" | relative_url}})

