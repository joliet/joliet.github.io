---
title: 'Kits Help Site'
subtitle: 'Content Strategy'
date: 2018-06-30 00:00:00
description: An example of content I've designed for a help site.
featured_image: '/images/demo/demo-square.jpg'
---


When I joined the Kits team in 2019, there was no documentation, just a form users could fill out requesting help.  And while the older version of the tool had a few documentation pages for most features, it lacked good information architecture and an easy way to search.

Adding complete documentation to the application was a high priority before we starting shifting all users to the newly redesigned tool.  I had the following goals for the design of the new documentation:

1. A search option would be prominent in the design.
2. The design and organization of the content would be inline with other supported tools.
3. It could easily be updated by everyone on the team including non-technical staff.
4. It had to be free and open source to align with our goal of open-sourcing the code.

I decided that Jekyll would be a good fit.  Luckily, I found a Jekyll documentation theme, Just the Docs, that was nearly a perfect fit.  Some minor styling was all that was needed to incorporate the documentation with the product.

The search box is persistent at the top of all documentation pages allowing users to quickly find the information they need.

![](/images/kits/kits_help.png)


### Image galleries

Here's a really neat custom feature we added – galleries:

<div class="gallery" data-columns="3">
	<img src="/images/demo/demo-portrait.jpg">
	<img src="/images/demo/demo-landscape.jpg">
	<img src="/images/demo/demo-square.jpg">
	<img src="/images/demo/demo-landscape-2.jpg">
</div>

Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a bit of simple HTML in your post to create a masonry grid image layout:

```html
<div class="gallery" data-columns="3">
    <img src="/images/demo/demo-portrait.jpg">
    <img src="/images/demo/demo-landscape.jpg">
    <img src="/images/demo/demo-square.jpg">
    <img src="/images/demo/demo-landscape-2.jpg">
</div>
```

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.

---
