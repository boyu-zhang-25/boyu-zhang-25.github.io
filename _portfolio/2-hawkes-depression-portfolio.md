---
title: "A Multivariate Hawkes Process for Detecting Individuals with Depressive Disorder"
excerpt: "We propose a personalized framework for classifying individuals with and without depression symptoms based on a mutual-exciting point process that captures both the temporal and semantic aspects of online activities.<br/><mark><i>Machine Learning &rarr; Temporal Point Process; Mental Health.</i></mark><br/><img src='/images/hawkes-depression-2.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->


>Machine Learning --> Temporal Point Process; Mental Health.

- Depressive disorder is one of the most prevalent mental illnesses among the global population. However, traditional screening methods require exacting in-person interviews and may fail to provide immediate interventions. In this work, we leverage ubiquitous personal longitudinal Google Search and YouTube engagement logs to detect individuals with depressive disorder. 

- We collected Google Search and YouTube history data and clinical depression evaluation results from $212$ participants ($99$ of them suffered from moderate to severe depressions). We then propose a personalized framework for classifying individuals with and without depression symptoms based on a mutual-exciting point process that captures both the temporal and semantic aspects of online activities. Our best model achieved an average F1 score of $0.77 \pm 0.04$ and an AUROC of $0.81 \pm 0.02$.

- **My Contribution**: I was the first author of this paper. I simulated the interplay between the distributional semantics and the temporal stochasticity of online activities with a mutually exciting multidimensional Hawkes Process.<br/><img src='/images/hawkes-depression-2.png'><br/>Through clustering, I first identified a set of implicit topics and labeled all the online interactions. Then, by modeling the labeled longitudinal online interactions with the multidimensional Hawkes Process, I obtained promising results in detecting depression symptoms.<br/><img src='/images/hawkes-depression-results.png' width='500' height='300'><br/>

- Please see our lightning talk at the NeurIPS 2020 Workshop on Machine Learning for Public Health [here](https://sites.google.com/nyu.edu/mlph2020/accepted-papers). The paper can be found [here](https://arxiv.org/abs/2010.15670). 
