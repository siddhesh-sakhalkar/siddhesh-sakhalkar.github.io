---
title: People
nav:
  order: 3
  tooltip: About our Team
---

# {% include icon.html icon="fa-solid fa-users" %}**People**

We are actively looking for motivated undergraduate, graduate (Masters/PhD) and post-doctoral candidates to join our team! If you would like to join us, please contact Prof. Sakhalkar (siddheshsakhalkar1992@gmail.com) and include your CV with research interests. We welcome researchers from diverse backgrounds including mechanical engineering, civil engineering, applied mathematics, computer science, data science & AI and related fields.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
