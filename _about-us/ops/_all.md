---
title: Product Operations
permalink: /about-us/ops
---

## **Product Operations**

{%- assign people = site.data.people | where: "functionId", "ops" | sort: 'name' -%}
{% include people-of-OGP.html people=people color=site.colors.function-colors.ops %}