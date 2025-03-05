---
layout: home
title: COSMOS
nav_order: 1
nav_exclude: false
seo:
  type: Workshop
  name: Cosmos
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<img src="{{site.baseurl}}/assets/images/tokyo.jpg" title="Photo by David Kernan under CC4.0">

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}
