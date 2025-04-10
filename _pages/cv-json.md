---
layout: archive
title: ""
permalink: /cv-json/
author_profile: true
redirect_from:
  - /resume-json
---
{% include base_path %}

<link rel="stylesheet" href="{{ base_path }}/assets/css/cv-style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 0;
  }

  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }

  .cv-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
  }

  .cv-download-links .btn {
    margin-left: 1rem;
    white-space: nowrap;
  }
</style>

<!-- Header section with title and download link side-by-side -->
<div class="cv-header">
  <h1>Curriculum Vitae</h1>
  <div class="cv-download-links">
    <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  </div>
</div>


## Education

* **Ph.D. in Biostatistics**, University of Pittsburgh (Aug 2021 – May 2026, GPA: 3.85)  
* **B.S. in Statistics & B.S. in Mathematics**, University of North Carolina at Chapel Hill (Sep 2017 – May 2021, GPA: 3.85)  
  * Honors: Phi Beta Kappa, Dean’s List  

## Skills

* **Programming**:  
  R, R Shiny, Python, STATA, SQL, Bash (proficient); Java, C++, SAS (familiar)  
* **Statistical & ML**:  
  Bayesian modeling, optimization, machine learning, deep learning (PyTorch), causal inference  
* **Research**:  
  High-dimensional multi-omics, longitudinal analysis, circadian rhythmicity methods  
* **Tools & Platforms**:  
  Scanpy, Seurat, VAE, GMM, AWS, Google Colab, STAR, Hisat2  

## Professional Experience

* **Senior Statistician Intern**, Otsuka (May 2025 – Aug 2025)  
  - Contributed to the design and analysis of a clinical trial focused on kidney disease  
  - Assisted in preparing statistical analysis plans and clinical study reports  

* **Graduate Research Assistant**, UPMC – University of Pittsburgh (Aug 2021 – Present)  
  - Developed and applied Bayesian/machine learning models for large-scale omics data  
  - Investigated circadian biomarker detection techniques  
  - Performed multi-modal data integration and domain adaptation  

* **Graduate RA**, Department of Infectious Disease (Aug 2023 – Present)  
  - Employed GEE and mixed-effects models for HIV data  
  - Conducted a longitudinal mediation analysis on dry needling interventions  

* **Undergraduate RA**, Carolina Center for Neurostimulation (Aug – Dec 2019)  
  - Modeled cortical synchrony using Python and MATLAB  

* **Research Intern**, Hill-Rom, NC (Jun – Aug 2020)  
  - Performed exploratory analyses and literature review for pediatric sepsis prediction  

## Deep Learning Projects

* **Phoneme Recognition**  
  - Employed CNNs, RNNs, and VAEs for accurate audio-text alignment  
* **Diffusion Models**  
  - Implemented DDIM and EMA on ImageNet-100 to explore class-specific performance  

## Publications

<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

<!--
## Talks

<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>
-->

## Teaching Experience

* **Graduate TA**, University of Pittsburgh  
  - BIOST 2086: Mixed Models (Spring 2024)  
  - BIOST 2050: Longitudinal Data Analysis (Fall 2023)  
  - BIOST 2041: Statistical Methods (Spring 2022)  
  - BIOST 2038: Statistical Theory (Fall 2021, 2022)  

* **Institute for Clinical Research Education**  
  - CLRES 2020/2005: Biostatistics & Computing (Summers 2022, 2024)  

* **Undergraduate TA**, UNC-Chapel Hill  
  - MATH 547: Linear Algebra (Fall 2019)  

## Awards

* Travel Funding Award – STATGEN Conference, 2025
* Dean's Day Biostatistics Doctoral Award (2025)
* Outstanding Teaching Assistant (TA) Award (2025)
* Phi Beta Kappa, UNC (Top 1%)  
* ICCA Semi-Finalist (2019 & 2020)  
* Multiple “Outstanding Student” awards, Pham Ngoc Thach University  
* City-Level Biology Olympiad Winner (2013 & 2014)  

## Leadership & Membership

* Member, ASA – Pittsburgh Chapter  
* Member, Pittsburgh Men’s Glee Club  
* Fundraising Committee, Tar Heel Voices (UNC)  
* Class President, Pham Ngoc Thach University (2014–2016)

