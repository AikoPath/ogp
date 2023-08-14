---
title: Yan, Sonjia
permalink: /people/syan
description: "Yan, Sonjia - Serious Title"
id: syan
name: Yan, Sonjia
joinDate: 2019-04-09
function: pm
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: It’s all about the quality of life and finding a happy balance between
  work and friends and family.
linkedinId: syan

---

{%- assign staff = site.data.people | find: "id", "{{page.id}}" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.pm %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}
