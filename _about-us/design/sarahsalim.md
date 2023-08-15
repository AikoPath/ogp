---
title: Salim, Siti Sarah
permalink: /aboutus/design/sarahsalim
description: "Salim, Siti Sarah - Job Title"
third_nav_title: Product Design
id: sarahsalim
name: Salim, Siti Sarah
joinDate: 1970-01-01
functionId: design
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: My family is my life, and everything else comes second as far as what’s
  important to me.
linkedinId: sarahsalim

---

{%- assign staff = site.data.people | find: "id", "sarahsalim" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.design %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}