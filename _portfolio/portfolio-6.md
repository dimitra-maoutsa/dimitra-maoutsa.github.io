---
title: "Inferring synaptic interactions and transmission delays"
excerpt: >-
  Inference of neuronal interactions from spike train recordings from a geometric approximation of the inter-spike interval generating function of each recorded neuron - **with Jose Casadiego\*, Dimitra Maoutsa\*, Marc Timme**
  <br/><img src="/images/event_space.png" alt="Geomteric approximation of inter-spike interval generating function—Dimitra Maoutsa" width="460" style="display:block; margin:0 auto;" />
collection: portfolio
---



We proposed a **mapping of the spiking activity to high-dimensional spaces**, termed **event spaces**, spanned by the inter-spike intervals of a selected neuron and the respective cross-spike intervals of the rest of the network. The mapping from the raster plot to the event spaces may be viewed as a sampling of the inter-spike interval generating function for each neuron. To **identify the effect of putative pre-synaptic neurons** to a post-synaptic one we proposed a **geometric approximation** of the inter-spike interval generating function around a reference point (reference event).
To **identify the transmission delays**, we proposed the minimisation of the approximation error in the space of interaction delays. To speed up the optimisation and avoid local minima, we optimised the delays on a smoothed error landscape approximated by radial basis function interpolation.


**Resulted in the paper [Casadiego\*, Maoutsa\*, Timme; Physical Review Letters 20218](https://gitlab.com/di.ma/Connectivity_from_event_timing_patterns/-/blob/master/PhysRevLett.121.054101.pdf)**


<img src='/images/event_space.png' alt="Mapping from raster plot to event spaces - Dimitra Maoutsa" style="max-width:600px; width:80%;" style="display:block; margin:0 auto;" >
