---
layout: page
permalink: /research/immune
title: Immune system sensing of gut bacteria
---

Resident bacterial populations within the intestine are highly dynamic, both in terms of spatial organization and abundances (see [here]({% link spatial.md %}) and [here]({% link models.md %})). How precisely do animals sense these dynamic changes occuring in their intestines? Being able to read out subtle and fast changes in bacterial behaviors would provide hosts with valuable information about ongoings in the gut, which is effectively an interface between an animal and its environment. Conversely, high sensitivity to microbial activities might pose a risk of persistant inflammation that would be detrimental to the host. To this point, misregulation of intestinal immune responses to gut microbes is thought to underly a variety of diseases including inflammatory bowel disease. 


We have begun to investigate these processes using larval zebrafish as model that enables spatially-resolved observation of both bacterial and host immune dynamics through live imaging (see [here]({% link spatial.md %})). On the host side, we make use of transgenic zebrafish engineered with fluorescent reporters of immune cell activities. In particular, we use a green fluorescent protein (GFP) reporter of gene expression of the canonical pro-inflammatory cytokine TNF&#945;. On the bacteria side, we use gnotobiotic techniques to raise fish devoid of any microbes and then study individual bacterial species and how they interact with the host immune system. We recently characterized a zebrafish gut bacterial isolate that, while being a common member of the conventional zebrafish gut microbiota and not causing overt disease, stimulates immune activity in a manner dependent of its swimming behavior [1].

![example microscopy image]({{site.baseurl}}/assets/tnf_example.png)

> Figure 1: Visualizing bacteria-immune cell interactions in larval zebrafish. Top: schematic of a 6 day-old zebrafish, with the anterior gut region of the image below indicated by a box. Bottom: a single optical plane showing bacteria in the intestine (magenta; native zebrafish strain *Vibrio* ZWU0020) and zebrafish cells expressing the pro-inflammatory cytokine TNF&#945; (green; Tg(tnfa:GFP)). Separate experiments revealed that the majority of gut-associated TNF&alpha;+ cells are macrophages. Image acquired with light sheet fluorescence microscopy.


<video width="320" height="240" autoplay controls>
  <source src="{{site.baseurl}}/assets/tnf_movie.mp4" type="video/mp4">
</video>
  
> Movie 1: Bacteria (magenta) swimming in a larval zebrafish gut localize close to the epithelium boundary. Immune cells respond by expressing the pro-inflammatory cytokine TNF&#945; (green; transgenic GFP reporter). Movie is in real time and captures a single optical z-plane of the same fish as in Fig. 1. Scale bar: 25 &mu;m.
> 

Swimming motility enables bacteria to access space close to intestinal epithelium, where their pro-inflammatory molecues are more easily sensed by immune cells. When the same species of bacteria is mutated to lose the ability to swim (by knocking out the flagella stator proteins pomAB; named "&Delta;mot"), we find that bacteria are more aggregated, are confined to the center of the gut, away from the epithelium, and induce substantially reduced immune response.


![example microscopy image]({{site.baseurl}}/assets/tnf_wt_mot_fig.jpg)

> Figure 2: Representative images of live larval zebrafish containing bacteria (magenta) and engineered with a green fluorescent protein reporter of the pro-inflammatory cytokine TNF&alpha; (green). Left shows the wild type bacteria (a *Vibrio* species native to the zebrafish gut). The bright magenta signal is a swarm of motile bacteria that are too dense and too fast for single cells to be resolved (see Movie 1 above). Right shows the same species engineered to be motility deficient. Large magenta objects are multicellular bacterial aggregates. Approximate gut boundary is shown as the dashed yellow line. The green TNF&alpha; reporter shows that the immune reponse to the wild-type bacteria is both local, within the gut tissue, and systemic, appearing in a region outside the gut confirmed to be the liver. The motility mutant elicits a substantially muted immune response. Images are maximum projections of 3D image stacks acquired with light sheet fluorescence microscopy.


Using this model of motility-dependent immune response, we are investigating the degree to which the host senses changes in bacterial swimming behaviors. In particular, in collaboration with [Travis Wiles](https://hostmicrobenexus.org/) of the [Guillemin lab](http://molbio.uoregon.edu/guillemin/) at UO, we are studying bacteria engineered inducible versions of motility mutations. With these switches, we can colonize fish with bacteria (the same native *Vibrio* species)  that cannot swim, and then at a later time give them the ability to swim simply by adding an inducer molecule to the fish water (the switch is based on tet-repressor circuitry, induced with anhydrotetracycline). Remarkably, upon induction of motility we observe an increase in TNF&alpha; expression over the course of 2 days that follows the shift of the bacterial population from non-motile to motile [1]. We are currently probing these dynamics further and working to untangle the roles of bacterial abundance, spatial organization, and active swimming activity in generating this motility-dependent immune response.

#### Papers:

[1] Travis J Wiles\*, Brandon H Schlomann\*, Elena S Wall, Karen Guillemin, Raghuveer Parthasarathy, Swimming motility and chemotaxis control the spatial organization, persistence, and inflammatory activity of a model intestinal pathobiont, [bioRxiv (2019) doi: https://doi.org/10.1101/779983](https://www.biorxiv.org/content/10.1101/779983v1)

#### [Back to Research]({{site.baseurl}}/research)
