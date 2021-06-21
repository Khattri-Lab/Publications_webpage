---
title: Home
---

# synergize microscopy, machine vision and AI 

We believe AI-based microscopy machine vision research requires a highly interdisciplinary field requiring good knowledge of machine learning, computer vision, microscopy and the associated biomedical applications. For example, applying deep learning on a specifcal microscopy image analysis problem is much more than collecting a bunch of images, making annotations, and throwing the data into a neural network. How to evaluate the quality of your data annotation? What if different people have slightly different annotations? How can I annotate the minimal amount of data to achieve to desired accuracy? ... 

On the other hand, the quantitative tasks in many biomedical applications may not be easily formulated into common deep learning based computer vision problems, such as segmentation, classification, image reconstruction, etc.. Even a problem can be formulated, we may face very different challenges in the specific biomedical context than the problem's original general computer vision setting. For example, it would be easy for everyone to accuratly annotate the contour of a car in a 2D image, but it could be very difficult the annotate the boundary of a nucleus in a 3D confocal microscopy image. It is not only because 3D is hard, but also because you have to take the diffraction of light into account to avoid over-segmentation. Similarly, minor segmentation error of cars may not be a big deal, but minor segmentation error of nuclei (e.g., over-smoothed boundary of nuclei with complext shape when being squeezed) may yield very different biomedical findings. So, to develop a successful AI-based microscopy image analysis algorithm, it is very important to have good understanding of microscopy and the underlying biomedical application.

Of course, no one can know all. So, we embrace a diverse group and extensive internal and external collaboration. 

{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.svg" %}

{% include section.html %}

# Highlights

{% capture text %}

AI-based microscopy machine vision is a highly multi-disciplinary field. There are so many fanscinating problems to explore and study.

[See our research landscape &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/researcg2.svg"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}

Our group is fully commited to open science, such as open source softwares/packages, public datasets, open access publications. We believe open science can lead to impactful big science.

[Visit our open science portal &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/open.svg"
  link="resources"
  headline="Our Resources"
  text=text
%}

{% capture text %}

We are building a team with diverse background and expertises, from software enigneering, machine learning, image analysis, data analysis to micr0scopy and computational biomedical modeling. 

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team.svg"
  link="team"
  headline="Our Team"
  text=text
%}
