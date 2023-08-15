---
title: Loke Swen, Jessendra
permalink: /aboutus/pm/jessendra
description: "Loke Swen, Jessendra - Job Title"
third_nav_title: Product Management
id: jessendra
name: Loke Swen, Jessendra
joinDate: 1970-01-01
functionId: pm
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is the heart of a home.
linkedinId: jessendra

---

{%- assign staff = site.data.people | find: "id", "jessendra" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.pm %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}