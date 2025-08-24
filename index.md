---
layout: home
title: Welcome to cynapse-zip
permalink: /
---

{%- capture readme -%}
{%- include_relative README.md -%}
{%- endcapture -%}

{{ readme | markdownify }}
