---
layout: home
title: Welcome to cynapse-zip
permalink: /
show_content: true
---

{%- capture readme -%}
{%- include_relative README.md -%}
{%- endcapture -%}

{{ readme | markdownify }}
