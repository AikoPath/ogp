---
title: Yu Ling, Tan
permalink: /aboutus/eng/yuling
description: "Yu Ling, Tan - Job Title"
third_nav_title: Software Engineering
id: yuling
name: Yu Ling, Tan
joinDate: 25/09/2023
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: A happy family is but an earlier heaven.
linkedinId: yuling

---

{%- assign staff = site.data.people | find: "id", "yuling" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}