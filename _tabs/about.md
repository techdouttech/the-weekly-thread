---
title: About
icon: fas fa-info-circle
order: 4
---
{% include staffResources.html %}
> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
{: .prompt-tip }

{% include hosts.html %}

{% include staffsingle.html user=site.data.staff.chi tableStart=true greeting=true %}
{% include staffsingle.html user=site.data.staff.duff %}
{% include staffsingle.html user=site.data.staff.hex tableEnd=true %}
{% include staffsingle.html user=site.data.staff.zeus tableStart=true %}
{% include staffsingle.html user=site.data.staff.kenzi %}
{% include staffsingle.html user=site.data.staff.kayla tableEnd=true %}
{% include staffsingle.html user=site.data.staff.je solo=true %}