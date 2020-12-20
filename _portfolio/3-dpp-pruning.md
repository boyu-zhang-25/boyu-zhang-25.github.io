---
title: "Understanding Diversity-based Pruning of Neural Networks -- Statistical Mechanical Analysis"
excerpt: "Despite multitude of empirical advances, there is no theoretical understanding of the effectiveness of different pruning methods. We address this issue by setting up the problem in the statistical mechanics formulation of a teacher-student framework and deriving generalization error (GE) bounds of specific pruning methods.<br/><mark><i>Machine Learning &rarr; Statistical Mechanical Analysis.</i></mark><br/><img src='/images/dpp-pruning-new.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->


>Machine Learning --> Statistical Mechanical Analysis.

- Deep learning architectures with a huge number of parameters are often compressed using pruning techniques to ensure computational efficiency of inference during deployment. Despite the multitude of empirical advances, there is no theoretical understanding of the effectiveness of different pruning methods. We address this issue by setting up the problem in the statistical mechanics formulation of a teacher-student framework and deriving generalization error (GE) bounds of specific pruning methods. This theoretical premise allows comparison between pruning methods, and we use it to investigate the compression of neural networks via diversity-based pruning methods. 

- Recent works showed that Determinantal Point Process (DPP) based node pruning method is notably superior to competing approaches when tested on real datasets. Using GE bounds in the setup mentioned above, we provide theoretical guarantees for their empirical observations. 

- Another consistent finding in the literature is that sparse neural networks (edge pruned) generalize better than dense neural networks (node pruned) for a fixed number of parameters. We use our theoretical setup to prove that the baseline random edge pruning method performs better than the DPP node pruning method. 

- Finally, we draw motivation from our theoretical results to propose a DPP edge pruning technique for neural networks that empirically outperforms other competing pruning methods on real datasets.

- **My Contribution**: I am the second author of this paper. I completed theoretical proofs of the generalization error bounds for a series of diversity and weight-based pruning methods on feed-forward neural networks in a group of two. We employed a statistical mechanics setup and characterized the network training process as ODEs. I further implemented a novel diversity-based edge pruning algorithm based on Determinantal Point Processes, which was inspired by the advance in neurophysiology on synapse diversity and elimination for energy conservation. We observed improved performances than previous methods in the same family on both synthetic and real-world datasets. <br/><img src='/images/dpp-pruning-old.png' width='500' height='300'><br/>

- Please see our paper [here](https://arxiv.org/abs/2006.16617).  

