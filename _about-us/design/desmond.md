---
title: Lui, Desmond
permalink: /aboutus/design/desmond
description: "Lui, Desmond - Job Title"
third_nav_title: Product Design
id: desmond
name: Lui, Desmond
joinDate: 1970-01-01
functionId: design
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: The family – that dear octopus from whose tentacles we never quite
  escape, nor, in our inmost hearts, ever quite wish to.
linkedinId: desmond

---

{%- assign staff = site.data.people | find: "id", "desmond" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.design %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}