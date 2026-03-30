---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are not currently accepting new positions but for information regarding the lab or the research being conducted please feel free to contact the team.

{%
  include button.html
  type="email"
  text="inquiry@delacylab.org"
  link="inquiry@delacylab.org"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/ePWdbqscuzPfYvAN8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/colorow.jpg"
  caption="Department of Psychiatry, University of Utah"
%}
<!-- https://www.google.com/maps/contrib/107412532859655679509/photos/@28.1142071,-96.2263203,4z/data=!3m1!4b1!4m3!8m2!3m1!1e1?entry=ttu&g_ep=EgoyMDI2MDIyMy4wIKXMDSoASAFQAw%3D%3D -->

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/living-room.jpg"
  caption="Living Room hike."
%}
<!-- https://www.visitsaltlake.com/blog/stories/post/the-best-hiking-trails-near-salt-lake/ -->

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
