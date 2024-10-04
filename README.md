# Noticeboard

This repository defines the content for the DIDE noticeboard website, and publishes the site on GitHub Pages to
https://mrc-ide.github.io/noticeboard/ 

The site is built with [Hugo](https://gohugo.io/), using the [Beautiful Hugo](https://github.com/halogenica/beautifulhugo.git) 
theme (referenced as a submodule)

## Adding content

All content is written in [Markdown](https://github.com/halogenica/beautifulhugo.git).

To add a blog post which will automatically appear on the front page, create a new file in the `/content/post` folder, including
title, author and date metadata, as shown in the example "first post" file. 

To add a static page, create a new file in the `/content/page` folder. You can link to your page from other pages, or add it to the 
menu defined in `hugo.toml`, either as a top level item, or sub-menu item (by defining its `parent`). Pages can be 
organised into subfolders as required.

Images should be saved to `static/img` which are deployed to a top-level `img` folder. 
When including links to images, you'll need to set the image path relative to the page or post you're working in e.g. to link
to `img/frights_and_bites.png` from `page/social.md`, the path is `../../img/frights_and_bites.png`.

## Local testing

To test your content locally:
1. Install hugo, as described [here](https://gohugo.io/installation/). You may find that the default version of hugo available
for your operating system is too old to support the theme (this has been observed for Ubuntu). In this case you will need
to download the [latest package version](https://github.com/gohugoio/hugo/releases/latest) and install from that.  
2. Run `hugo server` and browse to http://localhost:1313. Content changes will be automatically built and reflected in the browser.

## Publishing

Content will be published automatically to https://mrc-ide.github.io/noticeboard/ on GitHub Pages, by a GitHub Action which runs when new commits are pushed or merged
to the main branch. 


