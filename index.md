---
title: Documentation theme for Jekyll (customized)
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
hide_sidebar: true
permalink: /
summary: This site contains some customizations for the documentation theme provided by @tomjohnson1492
---

## What is this?

This documentation theme is entirely based on Tom's [Documentation Theme for Jekyll](https://github.com/tomjohnson1492/documentation-theme-jekyll). Many thanks to Tom for this wonderful theme. <br /><br />

As I started to use this theme, I made some minor enhancements and have submitted to the main repo. I also started making some style changes that I like, which I am not entirely sure would benefit all users. So I started making those changes here. These changes, are of course open source and free to use and also adopt the MIT license, same as the original repo. <br /><br />

Enjoy.

## Branches

This repo follows the below branching strategy
* baseline - reflects the original repo. Will be synchronized from time to time.
* gh-pages - latest updates with my changes. This branch contains the code that powers this site.
* *`<feature-name>`* - a new branch is created everytime a new feature is to be implemented. Will be based on baseline unless it is dependent on the customizations I made. This branch will be deleted if merged into the original repo, if not it will live on.

## Customizations

The following customizations are currently implemented:
* Left align the logo in the footer
* Align the disqus comments across the width of the page container
* Remove extensions in the URLs and make all URLs relative. So now you can use the `baseurl` flag in `_config.yml` and have the docs generate to a subfolder and use `| relative_url` filter to convert a URL to a relative URL based on `baseurl`.

<br /><br />
Get started [here](/mydoc_index)

{% include links.html %}
