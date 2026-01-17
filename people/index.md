---
title: People
nav:
  order: 3
  tooltip: About our Team
---

# {% include icon.html icon="fa-solid fa-users" %}People

We are actively looking for motivated undergraduate, graduate (Masters/PhD) and post-doctoral candidates to join our team! If you would like to join us, please contact Prof. Sakhalkar (add-email) and include your CV with research interests and potential project ideas. We welcome researchers with different backgrounds in mechanical engineering, applied mathematics, computer science, data science/AI and related fields.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
