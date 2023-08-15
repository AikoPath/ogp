---
title: Loh Wan Hua, Nicole
permalink: /aboutus/eng/nicole
description: "Loh Wan Hua, Nicole - Job Title"
third_nav_title: Software Engineering
id: nicole
name: Loh Wan Hua, Nicole
joinDate: 1970-01-01
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: "Family: A social unit where the father is concerned with parking space,
  the children with outer space, and the mother with closet space."
linkedinId: nicole

---

{%- assign staff = site.data.people | find: "id", "nicole" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}