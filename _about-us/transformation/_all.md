---
title: Partnerships & Transformation
permalink: /about-us/transformation
---

## **Partnerships & Transformation**

{%- assign people = site.data.people | where_exp: "staff", "staff.functionId == 'transformation'" | sort: 'name' -%}
{% include people-of-OGP.html people=people color=site.colors.function-colors.transformation  %}