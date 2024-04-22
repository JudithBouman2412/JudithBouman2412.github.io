---
permalink: /
title: "Research"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my personal academic website. Here, I share my academic work and research interests. 

Currently I am a postdoc at the University of Bern working on a project funded by the [Multidisciplinary Center for Infectious Diseases](https://www.mcid.unibe.ch/) under the supervision of [Christian Althaus](https://calthaus.github.io/) and [Julien Riou](https://www.unisante.ch/fr/formation-recherche/annuaire-chercheurs/chercheur/riou-julien). The project title is "Early detection for early action: integrating multiple data
sources for monitoring the SARS-CoV-2 epidemic in near
real-time" and includes work on transmission modelling of SARS-CoV-2 in Switzerland as well as developing causal inference methods for routinely collected hospital data. More information about these and other projects can be found below.  

Causal inference
======

I am working on testing and applying Natural Language Processing (NLP) enhanced causal inference methods for analysing routinely collected hospital data. For this project, I use data from the Insel Gruppe in Bern and collaborate with a range of medical and statistical expert from the Insel Gruppe and the University of Bern. 

Transmission modelling
======

I, together with Julien Riou, Christian Althaus and others, develped a Bayesian framework for implementing a time-varying transmission rate in compartmental infectious disease models. We did this in the R interface for Stan and published the work [here](https://judithbouman.ch/publication/2024_bayesian). The code can be found [here](https://github.com/judithBouman2412/HETTMO). The models are fitted to case counts (infections confirmed by a postive test) and serological data of an infectious disease. Currently, the model and code are parametrized for SARS-CoV-2 transmission, but can be adapted to other respiratory infectious diseases. 

If you are keen on using the framework for your research and need help to adjust it to your disease/situation of interest, please feel free to contact me. I am always happy to help. 

Serological data
======

Serological data is crucial for understanding the dynamics of infectious disease transmission. For an endemic disease, serological data can help to estimate the population immunite against the disease, the duration of immunity and the force of the infection. For newly emerging infectious diseases, seroprevalence data can give an indication of the number of cumulative infections and help to estimate the fraction of infections that is detected by the disease surveillance system. 

Most commonly, antibody measurements collected in a serosurvey are dichotomized (into seropositive and seronegative with a pre-defined cutoff value) to estimate the number of individuals that have been exposed to a disease. However, for population level estimates of the number of cumulative infections, dichotomization can actually cause a loss of statistical power for estimating cumulative incidence. Instead, it is possible to use the full distribution of antibody measurements in a "mixture model"-approach. [In this study](https://judithbouman.ch/publication/2021_cum_inc), I, together with Roland Regoes and others, compare the commonly used cutoff-based methods with a mixture model approach using simulated data to study the benifits of this methods for specific modelling assumptions. The code can be found [here](https://github.com/JudithBouman2412/PIST). In [a later study](https://judithbouman.ch/publication/2022_applying), we applied the mixture model method to SARS-CoV-2 seroprevalence data from Geneva, Switzerland. Here, we also exploited that severe SARS-CoV-2 infections give rise to a different distribution of antibody measurements compared to mild infections. 

In [a project led by dr. Sarah Kadelka](https://judithbouman.ch/publication/2023_correcting) we present a method for correcting for antibody waning in serosurvey data.   


Evolutionary modelling
======

During my PhD, Roland Regoes guided me in learning to think and model evolutionary processes within infectious disease modelling. [In a project on HIV-1 subtypes A, C and D](https://judithbouman.ch/publication/2023_virulence), we used two evolutionary models (one on a individual level and one on a population level) to explain the different velocities of spread of these subtypes. Key for this analysis was the estimation of the per-pathogen virulence of the three HIV-1 subtypes. The code of the study is published [here](https://github.com/JudithBouman2412/PerPathogenVirulence_HIVsubtypes). 

A second project on evolutionary infectious disease modelling, we, together with Celine Capelli, we investigate how the diversity in immune responses upon vaccination protects against the emergence of vaccine escape variants. For [this study](https://judithbouman.ch/publication/2021_vaccine), we developed the concept of escape depth. 
