---
layout: page
permalink: /research/abx
title: Effects of sublethal antibiotic exposure on gut bacteria
---


Antibiotic treatments induce large, sometimes irreversible changes in the composition of the gut microbiome. While potentially dangerous, due to unintended consequences of such extreme microbiome perturbations, that antibiotics alter microbiome composition is not altogether surprising given their lethality. What is suprising however is that antibiotics can lead to large alterations of microbiome composition even at very low, sublethal doses (see, e.g., [here](https://www.ncbi.nlm.nih.gov/pubmed/22914093)). In addition, low dose antibiotics are well known to alter animal physiology: since the 1940s, livestock have routinely been fed small amounts of antibiotics to increase their biomass. This effect still defies explanation, though [experiments](https://www.ncbi.nlm.nih.gov/pubmed/22914093) in a mouse model indicate that the gut microbiome is likely involved. Together, these disruptive effects of low dose antibiotics have raised concerns that antibiotics present in the environment---soil, water, and food---pose a public health risk independent of their role in disseminating drug resistance ([see here](https://www.ncbi.nlm.nih.gov/books/NBK481560/)).

One potential class of mechanisms underlying microbiome disruption by sublethal antibiotics involves the effects of these drugs on bacterial behavior and physiology at low concentrations. While molecular mechanisms vary across bugs and drugs, sublethal doses of antibiotics are generally known to drive bacteria into a more sessile lifestyle, marked by reduced division rates and increased display of biofilm-like behaviors. In addition, stress response pathways can be induced that alter the morphology of bacteria, for example, inducing filamentation:

![example model image]({{site.baseurl}}/assets/vib_cip_invitro_crop.jpg)
> Figure 1: Bacteria that have been treated with a low dose of antibiotics (here: ciprofloxacin, a broad spectrum fluoroquinolone) can become filamented as part of a stress response. This is a fluorescence microscopy image of bacteria on a glass slide.

Given our previous findings concering the important role that bacterial aggregation plays in overall population dynamics and stability (see [here]({% link models.md %})), we investigated the effects of sublethal antibiotics on gut bacteria using our zebrafish model and live imaging (see [here]({% link spatial.md %})).

We indeed found that sublethal doses of the widely used antibiotic ciprofloxacin leads to orders-of-magnitude greater reductions in the abundance of gut bacteria than would be predicted from in vitro measurements, and that this response is mediated by physical processes including aggregation [1]. Upon exposure to antbiotics bacteria shift to a more aggregated state in vivo, marked by fewer numbers of small clusters (Fig. 2). 

![example model image]({{site.baseurl}}/assets/ent_cip_full.jpg)

> Figure 2: Two representative fluoresence microscopy images of bacteria in live, larval zebrafish, one untreated (top) and one treated with a low dose of ciprofloxacin for 24 hours. Antibiotic treated fish have gut bacteria that are more aggregated, with fewer single cells and small clusters. Images are maximum intenisty projections of 3D image stacks obtained with light sheet fluorescence microscopy. Insets show examples of viability staining of expelled bacteria, where green indicates live bacteria and magenta indicates dead bacteria. We find that this low level of antibiotics does not lead to widespread killing of bacteria in the gut.

These small clusters turn out to function like a reservoir population that can re-seed the gut after large clusters are expelled from the gut:

<video width="640" controls>
  <source src="{{site.baseurl}}/assets/ent_expulsion.mp4" type="video/mp4">
</video>

> Movie 1: Time lapse imaging of fluorescent bacteria in a live, untreated larval zebrafish gut shows the expulsion of a large bacterial aggregate. Each frame is a maximum intensity projection of a 3D image stack acquired with light sheet fluorescence microscopy. Scale bar = 200 &mu;m. 

The depletion of single cells and small bacterial aggregates therefore leaves populations vunerable to complete extinction events and collapse of the population. This transition is captured mathematically by a [minimal mathematical model]({% link models.md %}) and is analogous to gelation transitions in soft materials.

#### Papers:

[1] Brandon H Schlomann\*, Travis J Wiles\*, Elena S Wall, Karen Guillemin, Raghuveer Parthasarathy, Sublethal antibiotics collapse gut bacterial populations by enhancing aggregation and expulsion, [bioRxiv (2019) doi: https://doi.org/10.1101/565556](doi: https://doi.org/10.1101/565556)

#### [Back to Research]({{site.baseurl}}/research)


 
