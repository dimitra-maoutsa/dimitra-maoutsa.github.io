---
title: "Contextual reconfiguration of representations"
excerpt: "  <br/><img src='/images/mouse.png' alt='Continual learning in RNNs-Dimitra Maoutsa'>"
collection: portfolio
---


Inter-area interaction analysis between V1 and adjacent areas reveals that V1 receives temporally resolved feedback from multiple areas during context-dependent computations.
Here we construct a multi-area model that explains these interactions.
<img src='/images/Inter-area.png' alt="Inter-area interactions- Dimitra Maoutsa" style="max-width:600px; width:100%;" >


Since during my last presentation some people asked me whether this work is similar to what I was doing in my previous lab or whether this is similar to other work done in my previous lab, let's point out the differences.

In my work in the previous lab, I was using the **two-photon Calcium imaging** visual behaviour dataset to model the emergence of prediction error responses in V1 in terms of **changes in recurrent interactions within V1**. This was a firing rate point neuron model, and I employed linear response thory to identify potential changes in the connections. **After** I left the lab, in **October 2024** I changed to analysing the neuropixels visual behaviour dataset to also be able to monitor responses of PV neurons, that I had to infer in the previous setting. **This present project is based on analysis of the neuropixels dataset, that provides also recordings from adjacent visual areas.**


However there are multiple hypotheses of how the prediction error responses emerge in the first place. One was the hypothesis I considered in my previous work, that assumes that all changes happen **within V1**. **Alternative hypotheses postulate that changes happen in the inputs that V1 receives, either feed-forward or feedback inputs.** This project explores this alternative hypothesis, of **feedback-driven changes**. The model for V1 considers a **two-compartment firing rate pyramidal neuron** and explores how the experimentally measured interactions between other areas and V1 influence the responses within V1.

- Does the project try to answer a similar question as my previous project? Yes.
- Is it the same project? No, because I start from a different hypothesis.
- Did I "borrow" work from my previous lab? No, because to the best of my knowledge existing work (that I was not involved in) considers top-down feedback and multi-compartment **spiking** neurons, **while the model I use comes directly from a publication of another lab**. (In fact in my preliminary work I performed experiments with two firing models coming from publications of two other labs. So this type of work to the best of my knowledge is being done in at least 4-5 competing labs, and is not exclusive to my previous lab. My main inspiration was in fact papers from these other labs.)

