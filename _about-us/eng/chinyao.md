---
title: Gan, Chin Yao
permalink: /aboutus/eng/chinyao
description: "Gan, Chin Yao - Job Title"
third_nav_title: Software Engineering
id: chinyao
name: Gan, Chin Yao
joinDate: 1970-01-01
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Rejoice with your family in the beautiful land of life.
linkedinId: chinyao

---

{%- assign staff = site.data.people | find: "id", "chinyao" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}