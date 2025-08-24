---
layout: home
title: Welcome to cynapse-zip
permalink: /
show_content: true
---

# Hi 🍋‍🟩

{% include_relative README.md %}


{%- capture readme -%}
{% include_relative README.md %}
{%- endcapture -%}

{{ readme | markdownify }}
