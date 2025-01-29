---
layout: page_research
permalink: /research/
title: research
# description: Research Interests
nav: true
nav_order: 6
---
# Research

<!-- For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->


I am broadly interested in exploring how **machine learning** can enhance the **monitoring, simulation, and control** of manufacturing and other engineering systems. From this intersection, three key research questions emerge that I intend to explore further:


<img src="/assets/img/research_interests.png" alt="Research Interests Diagram" style="max-width: 100%; height: auto;">
<!-- ![My Diagram]({{site.baseurl}}/assets/img/research_interests.png) -->



### Multi-fidelity Modeling with Machine Learning


High-fidelity simulations of physical behavior are often required to accurately model the behavior of complicated systems. However, the runtime and computational resources required for these simulations render them difficult to use for bulk analysis. Therefore, I am interested in developing methods to **accelerate** simulation-based analysis, such as surrogate models and multi-fidelity models that provide physics-informed insight with reduced computational demands.

{% include selected_papers_subset.liquid %}


### Navigating Uncertainty with Generative Deep Learning
<!-- Deep learning provides a powerful framework for probabilistic modeling, which can be used to create more reliable forecasts of system behavior. Specifically, challenges such as sensor limitations, noisy data, and modeling assumptions can be characterized to better understand the uncertainty associated with experimental observations and computational simulations. Therefore, I am interested in developing generative deep learning models that can capture probability distributions from sparse or noisy data, propagate uncertainty through high-dimensional systems, and ultimately improve confidence for decision-making and control scenarios. -->
Deep learning provides a powerful framework for probabilistic modeling, enabling more reliable forecasts of system behavior. In particular, it helps address challenges such as sensor limitations, noisy data, and modeling assumptions, all of which can introduce significant uncertainty into experimental observations and computational simulations. Therefore, I am interested in developing generative deep learning models that can characterize the probability distributions arising from sparse or noisy data, propagate uncertainty through high-dimensional systems, and ultimately **enhance confidence** in decision-making and control scenarios.

<!-- Deep learning provides a powerful framework for uncertainty quantification, enabling more reliable predictions in engineering and scientific applications. These methods help address challenges arising from sensor limitations, noisy data, and modeling assumptions, which can introduce uncertainty in both experimental observations and computational simulations. By leveraging techniques such as diffusion models and Bayesian neural networks, deep learning can efficiently navigate high-dimensional search spaces to characterize stochastic behavior, improving confidence in predictive outputs. This approach has broad applications across manufacturing, fluid mechanics, and design, where accurately capturing uncertainty is critical for optimizing performance and ensuring robust decision-making. By balancing computational expense with model accuracy, deep learning-based uncertainty quantification helps bridge the gap between simulation and real-world behavior, enabling more reliable predictions in complex, data-driven systems. -->

{% include selected_papers_subset_uncertainty.liquid %}


### Generalizable Machine Learning Models for Engineering Tasks
Machine learning applications in engineering contexts are often constrained by limited amounts of available labeled data, making it difficult to train reliable models at scale. Manual annotation is time-consuming and resource-intensive, restricting the effectiveness of these data-driven methods. The development of self-supervised and pre-trained models mitigates this challenge, by enabling models to learn structure from unlabeled data, that can be fine-tuned for specific applications. This approach also facilitates the development of generalizable **foundation models**, where a single model can be applied to a range of prediction tasks.

{% include selected_papers_subset_generalizable.liquid %}
