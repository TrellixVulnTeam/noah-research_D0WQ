# Bayesian Optimisation Research

This directory contains official implementations for Bayesian optimisation works developped by Huawei R&D, Noah's Ark Lab. 
- [HEBO: Heteroscedastic Evolutionary Bayesian Optimisation](https://github.com/huawei-noah/noah-research/tree/master/BO/HEBO) 
- [T-LBO](https://github.com/huawei-noah/noah-research/tree/master/BO/T-LBO)
- [Bayesian Optimisation with Compositional Optimisers](https://github.com/huawei-noah/noah-research/tree/CompBO/BO/HEBO/CompBO)

Further instructions are provided in the README 
files associated to each project.

## [HEBO](https://github.com/huawei-noah/noah-research/tree/master/BO/HEBO)
<img src="https://github.com/huawei-noah/noah-research/blob/master/BO/HEBO/hebo.png" alt="drawing" width="400"/>

Bayesian optimsation library developped by Huawei Noahs Ark Decision Making and Reasoning (DMnR) lab. The <strong> winning submission </strong> to the [NeurIPS 2020 Black-Box Optimisation Challenge](https://bbochallenge.com/leaderboard). 

## [T-LBO](https://github.com/huawei-noah/noah-research/tree/master/BO/T-LBO)
<p float="center">
  <img src="https://github.com/huawei-noah/noah-research/blob/master/BO/T-LBO/figures/LSBO.png" width="400" />
  <img src="https://github.com/huawei-noah/noah-research/blob/master/BO/T-LBO/figures/magnets.png" width="400" /> 
</p>

Codebase associated to: [High-Dimensional Bayesian Optimisation withVariational Autoencoders and Deep Metric Learning](https://arxiv.org/abs/2106.03609)
##### Abstract
We introduce a method based on deep metric learning to perform Bayesian optimisation over high-dimensional, structured input spaces using variational autoencoders (VAEs).
By extending ideas from supervised deep metric learning, we address a longstanding problem in high-dimensional VAE Bayesian optimisation, namely how to enforce
a discriminative latent space as an inductive bias. Importantly, we achieve such an inductive bias using just 1% of the available labelled data relative to previous work,
highlighting the sample efficiency of our approach. 
As a theoretical contribution, we present a proof of vanishing regret for our method. As an empirical contribution, 
we present state-of-the-art results on real-world high-dimensional black-box optimisation problems including property-guided molecule generation.
It is the hope that the results presented in this paper can act as a guiding principle for realising effective high-dimensional Bayesian optimisation.


## [Bayesian Optimisation with Compositional Optimisers](https://github.com/huawei-noah/noah-research/tree/CompBO/BO/HEBO/CompBO)

<div style="text-align:center"><img src="https://github.com/huawei-noah/noah-research/blob/CompBO/BO/HEBO/CompBO/image/summary-Best-performance-on-Synthetic-tasks-matern-52-3.png" alt="drawing" width="600"/>


Codebase associated to: [Are we Forgetting about Compositional Optimisers in Bayesian Optimisation?](https://arxiv.org/abs/2012.08240)
##### Abstract
Bayesian optimisation presents a sample-efficient methodology for global optimisation. Within this framework, a crucial performance-determining
subroutine is the maximisation of the acquisition function, a task complicated by the fact that acquisition functions tend to be non-convex and
thus nontrivial to optimise. In this paper, we undertake a comprehensive empirical study of approaches to maximise the acquisition function. 
Additionally, by deriving novel, yet mathematically equivalent, compositional forms for popular acquisition functions, we recast the maximisation
task as a compositional optimisation problem, allowing us to benefit from the extensive literature in this field. We highlight the empirical 
advantages of the compositional approach to acquisition function maximisation across 3958 individual experiments comprising synthetic optimisation 
tasks as well as tasks from Bayesmark. Given the generality of the acquisition function maximisation subroutine, we posit that the adoption of
compositional optimisers has the potential to yield performance improvements across all domains in which Bayesian optimisation is currently 
being applied.
