---
title: Chen, Wei Ian
permalink: /aboutus/eng/ian
description: "Chen, Wei Ian - Job Title"
third_nav_title: Software Engineering
id: ian
name: Chen, Wei Ian
joinDate: 2018-03-09
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: The family is one of nature’s masterpieces.
linkedinId: ian

---

{%- assign staff = site.data.people | find: "id", "ian" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}