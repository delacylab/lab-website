---
---

# de Lacy Lab

<!-- [Lab Website Template](https://github.com/greenelab/lab-website-template) is an easy-to-use, flexible website template for [labs](https://www.greenelab.com/).
Spend less time worrying about managing a website and citations, and more time running your lab. -->

The de Lacy Laboratory at the University of Utah uses computational tools and science to further mental health and substance use research.

<!-- {%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%} -->
{%
  include button.html
  type="github"
  text="On GitHub"
  link="delacylab"
%}

{% include section.html %}

## Highlights

{% capture text %}

Published research and studies conducted.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects/ember.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We have various active projects including, EMBER, TALOS, DYNAMOW, STRIDES, and ABCD. 

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects/minecraft.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Talented team with multi-disciplinary background.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
