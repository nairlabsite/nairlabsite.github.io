---
title: Research

nav:
  order: 2
  tooltip: Our research
---

# {% include icon.html icon="fa-solid fa-microscope" %} Research

{% capture text %}

Metastasis occurs when cancer cells spread from the primary tumor to other parts of the body. This spread is responsible for most cancer-related deaths. Because stopping metastasis is difficult in the clinic, developing better treatments to prevent cancer from spreading is critical to improving patient survival. Cell migration, or the process by which cells move, is essential for cancer cells to spread throughout the body. Our research focuses on understanding how epigenetic factors (which regulate gene activity without changing the DNA sequence) and biophysical factors (such as the stiffness of the environment surrounding cells) affect how cancer cells move and behave. In the Cancer Invasion and Metastasis Lab, we study how cancer cells move and spread using cell and mouse models, supplemented by bioinformatic analysis (the analysis of large sequencing datasets). By understanding what controls cancer cell movement, we hope to develop new treatments that can slow or stop cancer from spreading to other parts of the body. Our interests mainly follow three branches:

{% endcapture %}

{%
  include feature.html
  image="images/metastasis slides.png"
  text=text
  flip=true
  large=true
%}

{% include section.html %}

{% capture text %}

## 1. Discovering new drivers of metastasis through bioinformatics

Large-scale cancer datasets contain genomic and clinical information from thousands of patient tumors, providing a powerful resource for discovering new drivers of metastasis. By applying bioinformatic analyses to available datasets, we can identify genes that are consistently associated with cancer metastasis and prioritize the most promising candidates for further study. 

***What question does this address:*** Thousands of genes have been linked to cancer. Which genes drive metastasis?

***Why it matters:*** This approach enables rapid and cheap discovery of new drivers of metastasis that can subsequently be validated in the laboratory as potential therapeutic targets.

{% endcapture %}

{%
  include feature.html
  image="images/1. tcga identification.png"
  text=text
%}

{% include section.html %}

{% capture text %}

## 2. Studying the role of epigenetic factors in cancer progression

Epigenetic factors control when genes are turned on or off without changing the underlying DNA sequence. In the context of cancer, these epigenetic factors can activate genes that promote tumor growth and metastasis, or silence genes that normally suppress these processes. We investigate how epigenetic regulators alter gene activity to promote cancer cell migration, invasion, and metastatic spread. By identifying these regulators and the pathways they control, we aim to uncover new biology in cancers.

***What question does this address:*** Epigenetic factors are ubiquitous in cellular function, including in cancer cells. But, how they drive cancer progression and metastasis is poorly understood.

***Why it matters:*** Understanding how epigenetic factors drive cancer progression could reveal new therapeutic targets and lead to better cancer treatments.

{% endcapture %}

{%
  include feature.html
  image="images/2. epigenetics in cancer progression.png"
  text=text
  flip=true
  large=true
%}

{% include section.html %}

{% capture text %}

## 3. Understanding how biophysical factors influence epigenetics 

Biophysical factors, such as the mechanical forces that cells experience from their surrounding environment, can influence how genes are turned on and off. These forces alter the organization of DNA and its associated proteins, changing the activity of genes that control cell behavior. We study how mechanical forces from the tumor environment alter epigenetic regulators and gene expression, ultimately influencing cancer cell movement and metastatic behavior.

***What question does this address:*** Cells, including cancer cells, experience physical forces as they grow and spread. Yet, how these mechanical cues influence gene regulation and vice versa is not well understood.

***Why it matters:*** Understanding how physical cues regulate epigenetic processes could reveal new biology, which could be exploited for better therapeutic opportunities. 


{% endcapture %}

{%
  include feature.html
  image="images/3. biophysics of epigenetics.png"
  text=text
  large=true
%}