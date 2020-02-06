---
layout: post
title: Ways to communicate science using Github
tags: 'Science communication, Github websites'
excerpt_separator: <!--more-->
published: true
---

A large part of science is communication. After all, if we can't explain the purpose of our research, then why should people support us? One way research can be made more accessible is by building websites that delineate the research objectives and allow ordinary people to learn about the research and perhaps implement it.
<!--more-->
For those of use whom are scientists but not necessarily computer scientists, a relatively simple way to do this by using Github.

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
open _config.yml_ file to adjust the url. If you want the website to be your github name, then add in your github name as the url and leave baseurl as "". 
>baseurl: ""
>url: "https://username.github.io"

Alternatively, if you want to add this as a subpath to your directory then the baseurl should be the name you want as the subpath:
>baseurl: "/sub-directory"
>url: "https://username.github.io/"

Finally, if you want to create a page completely independent of your user name then you should create a new organization, and then you can use the organization name as your website name.

![Your science will take off by using Github]({{ "/assets/img/pexels/snowy-owl_robert_holden_immature.jpeg" | https://github.com/}})

