---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
Title: Clicks Without Compromise
---
# Clicks Without Compromise

  
  Total number of keyboards: 
    {% assign keyboard_count = site.data.keyboards | size %}
    {{ keyboard_count }}

Total number of switches: 
{% assign switch_count = site.data.switches | size %}
    {{ switch_count }}
