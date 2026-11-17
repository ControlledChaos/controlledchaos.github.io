---
title: "Going With the Flow"
subtitle: "Developing with Liquid templates is getting easier."
post_image: "liquid.jpg"
categories: "ccdzine-website"
tags: [ "learning", "jekyll", "liquid", "GitHub" ]
---

Building a website on GitHub Pages, as I am this website, means developing in [Jekyll](https://jekyllrb.com/) and [Liquid](https://shopify.github.io/liquid/). It also involves HTML files and [Markdown](https://daringfireball.net/projects/markdown/) files. The HTML I have known for 25 years and markdown is easy. But Jekyll and Liquid I had to learn, and there is not a lot of help on the internet, unlike platforms like WordPress.

It breaks down roughly like this: Jekyll is in charge of the metadata of content files and the hierarchy of template files, as well as general website metadata. Liquid is in charge of when and how content is displayed, similar to how [PHP](https://www.php.net) works. Both live in HTML files and GitHub compiles it all into something that the web browser understands.

Going with the flow of Liquid came quickly to me because I was already good with PHP, which runs WordPress. However, there are differences and Liquid is not nearly as powerful as PHP.

The big breakthrough came with realizing that the combination of Jekyll and Liquid can be used as one can use "custom post types" and "custom fields" in WordPress. This is how I implemented categories and tags in blog posts, as well as in project pages. I used it to create widgets for the sidebar and the site footer, for the front page slideshow, and for the front page sections.
