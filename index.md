---
title: Home
nav:
  order: 1
  tooltip: Home
---

# **Mechanics, Modeling and Machine Learning (M<sup>3</sup>) Lab**
 
Welcome to the M<sup>3</sup> Lab at the Indian Institute of Technology (IIT) Madras! We work at the intersection of mechanics, mathematics and artificial intelligence to design, simulate and optimize next-generation systems and devices. In particular, we focus on developing physics-based and data-driven models to understand and predict the mechanical behavior of engineering systems across multiple length scales, from macro to micro and nano.

Complex static and dynamic phenomena in solid and fluid mechanics are typically governed by non-linear partial differential equations (PDEs). Our lab develops analytical techniques, numerical models (including Finite Difference, Finite Element, Finite Volume models) and state-of-the-art machine learning methodologies (such as neural operators, foundation models) for accurate and efficient solution of these PDEs. We use these models to support downstream tasks of practical relevance such as design optimization, uncertainty quantification and inverse problems, with applications in diverse domains including micro/nanofluidics, hydrodynamic and elasto-hydrodynamic lubrication, data storage (e.g., hard disk drives) and micro-electro-mechanical systems (MEMS).

{%
  include figure.html
  image="images/Home_image.png"
  width="750px"
%}

Fun fact about IIT Madras: in addition to being the [top ranked institute](https://www.iitm.ac.in/happenings/press-releases-and-coverages/celebrating-decade-excellence-iit-madras-tops-nirf-once#:~:text=The%20National%20Institutional%20Rankings%20Framework%20(NIRF)%20is,Development%20Goals**%20Ranked%20%231%2C%20introduced%20this%20year) in India, IIT Madras is also well-known for it's beautiful campus, boasting diverse flora and fauna. The picture on the header of our webiste is a real photograph of a couple of deer spotted on the campus! 

{% include section.html %}

## **<span style="font-size: 1.3em;">Highlights</span>**

{% capture text %}

Key areas of interest include Scientific Machine Learning (SciML) for engineering simulations, Micro- and Nanoscale Fluid Mechanics, Structural Mechanics & Dynamics and Tribology.

{%
  include button.html
  link="research"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Prof. Siddhesh Sakhalkar is the Principal Investigator of the M<sup>3</sup> Lab. As a new lab, we are actively looking for motivated undergraduate, graduate (Masters/PhD) and post-doctoral candidates to join our team!

{%
  include button.html
  link="people"
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
  title="People"
  text=text
%}

{% capture text %}

Please browse through our published work to learn more about our past research.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications"
  title="Publications"
  flip=true
  style="bare"
  text=text
%}
