---
title: "From geometry to dynamics: Learning overdamped Langevin dynamics from sparse observations with geometric constraints"
excerpt: "Introducing geometric inductive biases for learning stochastic systems - extended version of the last project of my PhD thesis  <br/><img src='/images/overview_1-min.png' alt='Schematic of geometric framework-Dimitra Maoutsa'>"
collection: portfolio
---


<img src='/images/overview_1-min.png' alt="Schematic on how to introduce geometric inductive biases into stochastic system inference - Dimitra Maoutsa" style="max-width:600px; width:100%;" >



We proposed a method for introducing **geometric inductive biases** into the inference of stochastic systems. \
The central idea is to **view the deterministic flow field as a scaffold upon which system states fluctuate**,
and to approximate this scaffold in terms of **distortions of a metric induced by the observations**. \
This effectively approximates the low-dimensional invariant density (empirical manifold) without the need to project to a lower dimensional space (whose dimensionality would be hard to
estimate due to the presence of fluctuations). \
The central premise then is that **geodesics** computed on the empirical manifold wrt the approximated metric consitute **the most probable path between consecutive observations in the Onsager-Machlup sense**. \
We employed this most probable path as a control constraint to perform path augmentation between consecutive observations, and employed these estimated latent paths for inference of th eunderlying flow field. 


