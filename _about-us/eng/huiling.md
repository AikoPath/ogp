---
title: Shi, Hui Ling
permalink: /aboutus/eng/huiling
description: "Shi, Hui Ling - Job Title"
third_nav_title: Software Engineering
id: huiling
name: Shi, Hui Ling
joinDate: 1970-01-01
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: "Blended families: woven together by choice, strengthened together by
  love, tested by everything, and each uniquely ours."
linkedinId: huiling

---

{%- assign staff = site.data.people | find: "id", "huiling" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}