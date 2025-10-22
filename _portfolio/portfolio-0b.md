---
title: "Contextual reconfiguration of representations"
excerpt: "  <br/><img src='/images/mouse.png' alt='Continual learning in RNNs-Dimitra Maoutsa'>"
collection: portfolio
---


Inter-area interaction analysis between V1 and adjacent areas reveals that V1 receives temporally resolved feedback from multiple areas during context-dependent computations.
Here we construct a multi-area model that explains these interactions.
<img src='/images/Inter-area.png' alt="Inter-area interactions- Dimitra Maoutsa" style="max-width:600px; width:100%;" >

Presented as a poster at:
- **Champalimaud Neuro-cybernetics Symposium - Oct 2025**
- **Bernstein Conference - Sep 2025**



Since during my last presentation some people asked me whether this work is similar to what I was doing in my previous lab or whether this is similar to other work done in my previous lab, I think it is prudent to clarify the differences:



In my work in the previous lab, I was using the **two-photon Calcium imaging** visual behaviour dataset to model the emergence of prediction error responses in V1 in terms of **changes in recurrent interactions within V1**. This was a firing rate point neuron model, and I employed linear response thory to identify potential changes in the connections. **After** I left the lab, in **October 2024** I changed to analysing the neuropixels visual behaviour dataset to also be able to monitor responses of PV neurons, that I had to infer in the previous setting. (This is evident also in my Bernstein 2024 abstract where I claim that PV are yet unobserved). **This present project is based on analysis of the neuropixels dataset, that provides also recordings from adjacent visual areas.**

The idea to look at the interactions from other areas came from one of the projects I did last year in the MCN summer school supervised by Sara Solla (who incidentally received a Bernstein Prize this year) to measure the interactions between ACC and V1 on the data I got from my friend Sarah. This was on August 2024. I let this idea sit for some time in my head and around April 2025 I started looking in the neuropixels data I had for similar interactions.


Next, there are multiple hypotheses of how the prediction error responses emerge in the first place. One was the hypothesis I considered in my previous work, that assumes that **all changes happen within V1**. **Alternative hypotheses postulate that changes happen in the inputs that V1 receives, either feed-forward or feedback inputs.** This project explores this alternative hypothesis, of **feedback-driven changes**. The model for V1 considers a **two-compartment firing rate pyramidal neurons** and explores how the experimentally measured interactions between other areas and V1 influence the responses within V1.

- Does the project try to answer a similar question as my previous project? Yes.
- Is it the same project? No, because I start from a different hypothesis.
- Did I "borrow" work from my previous lab? No, because to the best of my knowledge existing work (that I was not involved in) considers top-down feedback and multi-compartment **spiking** neurons, **while the model I use comes directly from a publication of another competing lab**. (In fact in my preliminary work I performed experiments with two firing rate models coming from publications of two other labs. So this type of work to the best of my knowledge is being done in at least 4-5 competing labs, and is not exclusive to my previous lab. My main inspiration was in fact papers from these other labs.)

- **However if someone thinks otherwise and believes that I have "claimed part of their work/their ideas/their dreams" or whatnot, I am very open to discussion, and I am always reachable over e-mail. And I prefer to be contacted directly to resolve any issue, as opposed to let rumors spread that I am misappropriating work.**

