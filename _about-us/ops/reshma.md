---
title: Vasu, Reshma
permalink: /aboutus/ops/reshma
description: "Vasu, Reshma - Job Title"
third_nav_title: Product Operations
id: reshma
name: Vasu, Reshma
joinDate: 1970-01-01
functionId: ops
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Families are like fudge – mostly sweet with a few nuts.
linkedinId: reshma

---

{%- assign staff = site.data.people | find: "id", "reshma" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.ops %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}