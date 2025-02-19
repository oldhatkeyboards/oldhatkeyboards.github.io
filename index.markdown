---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home

---
# Old Hat Keyboards: Clicks Without Compromise

  
  <div role="region" aria-label="database stats">
  Total number of keyboards: 
    {% assign keyboard_count = site.data.keyboards | size %}
    {{ keyboard_count }}<br>
Total number of switches: 
{% assign switch_count = site.data.switches | size %}
    {{ switch_count }}
</div>
