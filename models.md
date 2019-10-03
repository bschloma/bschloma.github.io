---
layout: page
permalink: /research/models
title: Stochastic models of gut bacterial dynamics 
---


Motivated by the detailed data extracted from our images of bacteria in the zebrafish gut (see [here]({% link spatial.md %})), we have developed and studied minimal mathematical models that can be directly parameterized from data, make testable predictions, and bring insight into bacterial colonization of the gut.

## Kinetics of bacterial aggregation

![example model image]({{site.baseurl}}/assets/gac_model_schematic.jpg)

> Figure 1: Schematic of a kinetic model that describes the dynamics of bacterial cluster sizes in the intestine. Taken from [1].
> 

Inspired by the physics of soft materials like polymers, colloids, and Jell-O, we developed a mean-field kinetic model to describe the dynamics of individual bacterial clusters in the gut (Fig. 1). This model can be completely parameterized with a few routine measurements and was shown to make a fit-free prediction of the bacterial cluster size distribution that agrees remarkably well with data [1]. The model also gives insight into how the aggregation behavior of bacteria determines the large-scale stability of population in the face of intestinal fluid flow and can be used to make predictions about perturbations like antibiotics [1]. 

## Population dynamics with random catastrophes

![example model image]({{site.baseurl}}/assets/lrc_les_sample_paths.jpg)

> Figure 2: Sample paths from two models of stochastic population dynamics. A: Logistic growth with random catastrophes. B: Logistic growth with multiplicative Gaussian white noise. *X<sub>t</sub>* is the population size at time *t*, *K* is the carrying capacity, and *r* is the growth rate. Both models were studied analytically in [3].
> 

Bacterial aggregates in the gut are subject to fluid flows that transport them from one region of the gut to another. In the case of the larval zebrafish gut, this can result in the abrupt expulsion of aggregates from the gut altogether:

<video width="640" controls>
  <source src="{{site.baseurl}}/assets/ent_expulsion.mp4" type="video/mp4">
</video>

> Movie 1: Time lapse imaging of fluorescent bacteria in a live larval zebrafish gut shows the expulsion of a large bacterial aggregate. Each frame is a maximum intensity projection of a 3D image stack acquired with light sheet fluorescence microscopy. Scale bar = 200 &mu;m. 
 
These expulsion events register in a large, negative drop in the local bacterial abundance, reminiscent of catastrophic events in macroscopic ecosystems. We showed that in larval zebrafish, these events arrive in a manner consistent with a Poisson process: the events occur randomly, with a constant probability rate [2]. This stochasticity, coupled to the large size of the collapses, generates massive variation in intestinal abundance that far exceeds static, host-host variation. To understand how this variation is generated, we studied a minimal stochastic differential equation model of bacterial population dynamics coupled to discrete, random jumps [3]. Several analytic results were derived, including exact expressions for the stationary moments of this process, giving explicit insight into how random collapses generate variation in abundance and how several parameters of the model can be condensed into a single, effective parameter. In addition, the diffusion limit of this jump process was derived exactly, connecting the model to more well-known Langevin equations with Gaussian driving noise.

#### Papers:

[1] Brandon H Schlomann\*, Travis J Wiles\*, Elena S Wall, Karen Guillemin, Raghuveer Parthasarathy, Sublethal antibiotics collapse gut bacterial populations by enhancing aggregation and expulsion, in press at *PNAS* (2019), [bioRxiv (2019) doi: https://doi.org/10.1101/565556](doi: https://doi.org/10.1101/565556) 

[2] Travis J Wiles , Matthew Jemielita , Ryan P Baker, Brandon H Schlomann, Savannah L Logan, Julia Ganz, Ellie Melancon, Judith S Eisen, Karen Guillemin, Raghuveer Parthasarathy, Host Gut Motility Promotes Competitive Exclusion within a Model Intestinal Microbiota, [*PLoS Biology* (2016) DOI:10.1371/journal.pbio.1002517](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002517)

[3] Brandon H Schlomann, [Journal of Theoretical Biology **115**, 2271–2277, (2018)](https://www.sciencedirect.com/journal/journal-of-theoretical-biology/vol/454/suppl/C)

#### [Back to Research]({{site.baseurl}}/research)
