---
title: Png, Christabel
permalink: /people/christabelpng
description: "Png, Christabel - Serious Title"
id: christabelpng
name: Png, Christabel
joinDate: 2020-01-06
function: design
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is not an important thing. It’s everything.
linkedinId: christabelpng

---

{%- assign staff = site.data.people | find: "id", "{{page.id}}" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.design %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}
