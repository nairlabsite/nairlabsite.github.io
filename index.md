---
title: Home

nav:
  order: 1
  tooltip: Nair Laboratory home
---

<p style="text-align: center; font-size: 1.5rem; font-weight: 500;">
  NAIR LABORATORY <br> 
  Department of Applied Science | William &amp; Mary
</p>

{% capture text %}

Cancer metastasis - the spread of cancer cells from the primary tumor to distant organs - causes the vast majority of cancer-related deaths. Thus, developing effective therapies that limit or prevent metastatic spread is critical to improving patient survival. We study how epigenetic factors (which regulate gene activity without changing the DNA sequence) and biophysical factors (such as the stiffness of the environment surrounding cells) affect how cancer cells move and behave. 

We work at the interface of bioengineering, cancer biology, and pre-clinical animal models. By understanding what controls cancer cell movement, we hope to develop new treatments that can slow or stop cancer from spreading to other parts of the body. 

{% endcapture %}

{%
  include feature.html
  image="images/0. General metastasis.png"
  text=text
  flip=true
  large=true
%}

{%
  include button.html
  link="research"
  text="Explore Our Research"
  icon="fa-solid fa-arrow-right"
%}
{%
  include button.html
  link="team"
  text="Meet the Lab"
  icon="fa-solid fa-users"
%}

{% include section.html %}

## Research

{% capture text %}

Large-scale cancer datasets provide a powerful resource for discovering genes that enable cancer to spread. We use bioinformatics to identify promising candidates and experimentally validate their roles in cancer progression.

{%
  include button.html
  link="research"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/1. tcga identification 2.png"
  link="research"
  title="Bioinformatic Discovery of Metastatic Drivers"
  text=text
%}

{% capture text %}

Epigenetic factors regulate gene activity and can profoundly influence how cancer cells grow, move, and spread. We investigate how these regulators control cell migration and metastasis to identify new mechanisms and therapeutic vulnerabilities.

{%
  include button.html
  link="research"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/2. epigenetics in cancer progression.png"
  link="research"
  title="Epigenetics & Cancer Progression"
  flip=true
  text=text
%}

{% capture text %}

Cancer cells experience physical forces as they interact with their surrounding environment. We study how these biophysical cues influence epigenetic regulation, cell behavior, and metastatic progression.

{%
  include button.html
  link="research"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/3. biophysics of epigenetics.png"
  link="research"
  title="Biophysics & Epigenetics"
  text=text
%}

{% include section.html %}

## Join the Lab

If you are interested in our work and are considering joining us, please reach out to Prof. Nair.

{%
  include button.html
  link="join"
  text="Join the Lab"
  icon="fa-solid fa-arrow-right"
%}