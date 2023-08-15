---
title: Wong Zhi Qian, Sebastian
permalink: /aboutus/eng/sebastian
description: "Wong Zhi Qian, Sebastian - Job Title"
third_nav_title: Software Engineering
id: sebastian
name: Wong Zhi Qian, Sebastian
joinDate: 1970-01-01
functionId: eng
jobTitle: Job Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is not an important thing. It’s everything.
linkedinId: sebastian

---

{%- assign staff = site.data.people | find: "id", "sebastian" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}