---
title: Tan, Kevan
permalink: /aboutus/eng/kevan
description: "Tan, Kevan - Job Title"
third_nav_title: Software Engineering
id: kevan
name: Tan, Kevan
joinDate: 18/11/2019
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: To us, family means putting your arms around each other and being there.
linkedinId: kevan

---

{%- assign staff = site.data.people | find: "id", "kevan" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}