---
title: Chan, Tiffany
permalink: /people/tiffany
description: "Chan, Tiffany - Serious Title"
id: tiffany
name: Chan, Tiffany
joinDate: 1970-01-01
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is not an important thing. It’s everything.
linkedinId: tiffany

---

{%- assign staff = site.data.people | find: "id", "{{page.id}}" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}
