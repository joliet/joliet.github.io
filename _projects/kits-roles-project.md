---
title: 'Kits Roles'
subtitle: 'Usability Testing'
date: 2018-06-30 00:00:00
description: In this project, I conducted application and user research to learn how the team should design roles in the Kits product.
featured_image: '/images/demo/demo-square.jpg'
---


In 2019, I conducted usability testing for a new design and discovered that users were confused about role names and permissions in our product, Kits.  Kits is a middleware product that integrates with many other apps and has two different types of 'kits' - one for learning and one for collaboration. The same set of roles were used for both types - instructor, assistant, and student.  Users did not associate these role with collaboration kits, nor were they able to translate these roles across integrated apps.

---

Starting with what I learned through usability testing, I created a project plan to improve role naming.  

> **Problem**: Existing role names do not make sense to users in collaboration kits.

> **Hypothesis**: Role names used in other collaboration tools are expected.

> **Metric**: Users will select the correct role for collaborators based on permissions needed 85% of the time during the final round of usability testing.

The overall process would involve research of role names of integrated collaboration tools, more user research to understand users' mental models of roles names and permissions, selection of new roles based on this research and more usability testing.  


> **Research**  -->  **Usability Test** --> **Prototype** --> **Usability Test** --> **Roll out**

---

Since many other tools are connected to Kits, I started with an evaluation of roles across all integrated tools.

![](/images/kits/kits_apps_roles.png)

To better understand users' mental models of roles and permissions, I conducted a card sorting activity to learn how users would categorize roles across all integrated tools.

![](/images/kits/kits_roles_card_sort.png)

With the outcomes of this research, I created a new prototype in Invision with new role names - Owner, Editor, and Viewer - and re-tested role selection with users. Ninety percent of users correctly selected roles based on the role's permissions in the collaboration kit.

![](/images/kits/kits_roles_prototype.png)

---

**Outcome**

These role names have been added to the product. We have not received any negative feedback in user interviews about these roles, nor have we received support requests related to role confusion or mismatch.


---

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
