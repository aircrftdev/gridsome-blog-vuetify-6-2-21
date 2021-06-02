---
title: Blog-in-a-Box
date: 2021-06-03
published: true
tags: ['Blogging System', 'Tools & Solutions']
series: false
cover_image: ./images/aircrft-blog-in-a-box-cover-0.png
canonical_url: false
description: "A complete blogging system for startups"
---

<script src="https://gumroad.com/js/gumroad.js"></script>
<a class="gumroad-button" href="https://gumroad.com/l/zwIVA" target="_blank">Blog-in-a-Box | Buy Now</a>

###Vuetify app edition 6-2-2021 8am

### Custom image with javasript trigger

[![alt text
](https://raw.githubusercontent.com/aircrftdev/Aircrft-Dev-Staging-Landkit-2.0.0-beta1/cfaa64825a4469637ef300ab13dbf7bef7ab81b1/src/aircrft-brand-logo-white-600x135.png
"Blog in a Box Buy Now")
](https://gumroad.com/l/zwIVA)

### Custom image with javasript trigger

[![alt text
](https://raw.githubusercontent.com/aircrftdev/Aircrft-Dev-Staging-Landkit-2.0.0-beta1/master/src/img/buttons/button-app.png
"Blog in a Box Buy Now")
](https://gumroad.com/l/zwIVA)


### Custom image svg with javasript trigger

[![alt text
](https://raw.githubusercontent.com/aircrftdev/Aircrft-Dev-Staging-Landkit-2.0.0-beta1/cfaa64825a4469637ef300ab13dbf7bef7ab81b1/src/img/icons/magic-1.svg
"Blog in a Box Buy Now")
](https://gumroad.com/l/zwIVA)


### Custom image svg with javasript trigger

[![alt text
](https://github.com/aircrftdev/Aircrft-Dev-Staging-Landkit-2.0.0-beta1/blob/master/src/img/aircrft-brand-logo-menu-70x300.png?raw=true
"Blog in a Box Buy Now")
](https://gumroad.com/l/zwIVA)

### Markdown button test


[button url="http://www.google.com"]


{% include button.html url="http://www.google.com" %}


The third option is to write plain HTML:

Lorem ipsum dolor sit amet.

<button name="button" onclick="http://www.google.com">Click me</button>



Option 4. The markdown way

The last option is to use markdown to add a class and use CSS to style the link as a button.

Lorem ipsum dolor sit amet.

[Click me](http://www.google.com){: .btn}


<button name="button">Click me</button>


Use the include option (2) that JoostS recommended. Here's more specific info that shows how to incorporate a button using includes with parameters. In your _includes folder, create your button template (e.g., button.html), such as this:

<button type="button" class="btn btn-{{include.button_class}} active">{{include.button_name}}</button>
(This HTML code assumes you're using Bootstrap for your buttons.)

Those places where I've written {{include.button_name}} will be the parameters you pass into your include.

Now on your Markdown page, include your button like this:

{% include button.html button_name="My Button" button_class="primary" %}
I use this technique for callouts, images, and alerts in my documentation. Basically any time you have complex HTML formatting, you can hide it away in an include template like this.

Blog-in-a-Box

By  Aircrft

A complete blogging system for startups. 
Opens a universe of possibilities and opportunities. Product-ready out-of-the-box blogging platform powered by then latest server-less JAMstack architecture. 

⭐️ Startup-grade. 
⭐️ Fully-deployed production ready
⭐️ JAMstack architecture 
⭐️ Infinitely scalable
⭐️ blazing-fast
⭐️ bullet-proof secure
⭐️ Your custom domain 

💎 Aircrft Code Captains wire-up your domain blog.startup.com / startup.com/blog


Tier
$99 a year
Yearly
One year of Blogging awesomeness. We make sure your 100% set up and running smooth, including wiring up your startups custom domain name! 😀
