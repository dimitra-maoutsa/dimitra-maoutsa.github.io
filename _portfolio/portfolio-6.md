---
title: "Inferring synaptic interactions and transmission delays"
excerpt: >-
  Inference of neuronal interactions from spike train recordings from a geometric approximation of the inter-spike interval generating function of each recorded neuron <br/> **with Jose Casadiego\*, Dimitra Maoutsa\*, Marc Timme** <br/> before PhD
  <br/><img src="/images/event_space.png" alt="Geomteric approximation of inter-spike interval generating function—Dimitra Maoutsa" width="460" style="display:block; margin:0 auto;" />
collection: portfolio
---



We proposed a **mapping of the spiking activity to high-dimensional spaces**, termed **event spaces**, spanned by the inter-spike intervals of a selected neuron and the respective cross-spike intervals of the rest of the network. The mapping from the raster plot to the event spaces may be viewed as a sampling of the inter-spike interval generating function for each neuron. To **identify the effect of putative pre-synaptic neurons** to a post-synaptic one we proposed a **geometric approximation** of the inter-spike interval generating function around a reference point (reference event).
To **identify the transmission delays**, we proposed the minimisation of the approximation error in the space of interaction delays. To speed up the optimisation and avoid local minima, we optimised the delays on a smoothed error landscape approximated by radial basis function interpolation.

[Here](/files/Reco_connectivity_for_irregular_dynamics.pdf) is an extension of the method that I wrote up as a mini-project in prallel with my thesis that imporves the reconstruction performance in settings with irregular spiking activity. The clue in this case is to look at the singular components with less variability (minor components) because they represent the directions in the event space with consistent firing patterns that correspond to causal interactions between neurons, while the dominant/principal component capture the variability of the irregular activity.
This didn't make it in the final paper, but I've always found it a neat feat.


**Resulted in the paper [Casadiego\*, Maoutsa\*, Timme; Physical Review Letters 2018](https://gitlab.com/di.ma/Connectivity_from_event_timing_patterns/-/blob/master/PhysRevLett.121.054101.pdf)**

<p align="center">
  <img src="/images/event_space.png" alt="Mapping from raster plot to event spaces - Dimitra Maoutsa" width="58%">
  <img src="/images/event_space_representation.png" alt="Event space representation of raster plot - Dimitra Maoutsa" width="38%">
</p>

<p align="center">
  <img src="/images/reconstruction_quality_vs_CV.png" alt="Reconstruction quality vs CV - Dimitra Maoutsa" width="48%">
  <img src="/images/inferring_delays.png" alt="Inferring delays - Dimitra Maoutsa" width="48%">
</p>




