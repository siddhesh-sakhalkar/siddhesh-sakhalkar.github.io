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
  caption="Overview of M<sup>3</sup> Lab's research"
%}

Fun fact about IIT Madras: in addition to being the [top ranked institute](https://www.iitm.ac.in/happenings/press-releases-and-coverages/celebrating-decade-excellence-iit-madras-tops-nirf-once#:~:text=The%20National%20Institutional%20Rankings%20Framework%20(NIRF)%20is,Development%20Goals**%20Ranked%20%231%2C%20introduced%20this%20year) in India, it is also well-known for its beautiful campus, which is home to diverse flora and fauna. The header image on our website is a [real photograph](https://commons.wikimedia.org/wiki/File:Deer_of_IIT_Madras_masatran_0058_0010.jpeg) of a couple of deer spotted on the campus! 

{% include section.html %}

## **<span style="font-size: 1.3em;">Explore M<sup>3</sup> Lab</span>**

{% capture text %}

Key areas of interest include Scientific Machine Learning (SciML) for engineering simulations, Structural Mechanics and Dynamics (with emphasis on Design Optimization, Uncertainty Quantification and System Identification) and Fluid Mechanics (with a focus on micro- and nanoscale flows). Learn more about our ongoing research projects here.

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
  image="images/Research_highlights.jpg"
  link="research"
  title="Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Prof. Siddhesh Sakhalkar is the Principal Investigator of the M<sup>3</sup> Lab. We are actively looking for motivated undergraduate, graduate (Masters/PhD) and post-doctoral candidates to join our team! If you would like to join us, please contact Prof. Sakhalkar ([siddheshsakhalkar1992@gmail.com](mailto:siddheshsakhalkar1992@gmail.com)) and include your CV with research interests.

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
  image="images/Siddhesh_Sakhalkar_headshot_highlights.jpg"
  link="team"
  title="People"
  text=text
%}

{% capture text %}

Please review our published papers and patents to learn more about our prior research. In particular, we encourage you to explore our recent work that combines statistical analysis of measured population Frequency Response Function data with Finite Element Method simulations to predict device-to-device variations during high-volume manufacturing.

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
  image="images/Publications.jpg"
  link="publications"
  title="Publications"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our core expertise lies in developing theoretical frameworks, numerical models and machine learning methodologies to study static and dynamic problems in solid and fluid mechanics. If you are interested in collaborating with us on a research project, please feel free to contact us.

{%
  include button.html
  link="contact"
  text="Contact us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/colab.png"
  link="contact"
  title="Collaborations and Parternships"
  style="bare"
  text=text
%}
