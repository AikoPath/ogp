---
title: Ghwee, Ciqin
permalink: /aboutus/eng/ciqin
description: "Ghwee, Ciqin - Job Title"
third_nav_title: Software Engineering
id: ciqin
name: Ghwee, Ciqin
joinDate: 22/05/2023
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family gives you the roots to stand tall and strong.
linkedinId: ciqin

---

{%- assign staff = site.data.people | find: "id", "ciqin" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}