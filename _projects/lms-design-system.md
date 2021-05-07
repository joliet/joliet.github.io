---
title: 'Learning Managment System'
subtitle: 'Design System'
date: 2020-01-01
description: A design system project for an LMS.
featured_image: '/images/lms/design-system-square.png'
---


In 2017, I partnered with Duke's CrUX team to lead a project for an open source software community to develop a pattern library for their product.  The product was a learning management system (Sakai) which had been originally developed by four different universities that had merged their home-grown products into one.  While the product had been active with many contributors for more than a decade, UI inconsistencies were pervasive.

---

The first step in this project was to meet with a UX designer and visual designer on the CrUX team to build an understanding of the problems we were trying to solve, the scope of the project, and deliverables.  

***Problem*** : *The product had inconsistent design elements throughout including buttons, navigation, icons, and other UI elements.*

***Scope*** : *Only user-facing tools would be evaluated for UI inconsistencies; no admin tools would be considered as part of the project.*

***Deliverable*** : *A pattern library would be established for the product making it easier to fix current inconsistent designs and make new development easier and more consistent.*

<br>
We defined the following plan for the project:

***UI Inventory***  -->  ***Establish New Designs Patterns*** --> ***Build Consensus for Designs*** --> ***Research and Identify Pattern Library Solution***

---

My main role in the project was to facilitate the UI inventory as a community-wide project, coordinate discussions for consensus on designs, and to facilitate discussions with developers on next steps for pattern library product selection and implementation.  The new UI pattern designs were created by a visual designer on Duke's CrUX team.

**1. UI inventory**

In collaboration with the CrUX team, I created UI inventory template in Google Slides for each tool in our scope.

I created a Google Sheet to track the overall progress of the project.  Volunteers could sign up to inventory a specific tool and track their level of completion.

![](/images/lms/interface_inventory_signup.png)

**2. Establish new design patterns**

When the UI inventory was completed, I worked with a visual design on the CrUX team to create new UI patterns.  My role in her process was the product expert to help her understand the use cases for tools and top tasks for each.

**3. Build consensus for designs.**

When the new design patterns were ready, I connected the designer to the community to discuss the designs.  Issues and ideas would often come up that were out of scope for the project.  I tracked these for the community by creating new Jiras or Confluence pages in our project space.

**4. Research and identify pattern library solutions**

Part of this project was to select the right place for the new design patterns to live.  I partnered with a developer in the community to lead this aspect of the project.  I connected him with staff at Duke who had experience with Pattern Lab and other products.


---

**Outcome**

Development work to implement the new design patterns started within a month after the community adopted them.  Selecting a pattern library product proved more challenging.  Two developers are currently evaluating Storybook.


![](/images/demo/demo-landscape.jpg)

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
