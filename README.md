# Noticeboard

This repository contains the content for the DIDE noticeboard website, and publishes the site on GitHub Pages. 

The site is built with [Hugo](https://gohugo.io/), using the [Beautiful Hugo](https://github.com/halogenica/beautifulhugo.git) 
theme (referenced as a submodule)

## Adding content

All content is written in [Markdown](https://github.com/halogenica/beautifulhugo.git).

To add a blog post which will automatically appear on the front page, create a new file in the `/content/post` folder, including
title, author and date metadata, as shown in the example "first post" file. 

To add a static page, create a new file in the `/content/page folder`. You can link to this from other pages, or add it to the 
menu defined in `hugo.toml`, either as a top level item, or sub-menu item (by defining its `parent`). Pages can be 
organised into subfolders as required.

Images should be saved to `static/img`

## Publishing

Content will be published automatically to GitHub Pages, by a GitHub Action which runs when new commits are pushed or merged
to the main branch. 

