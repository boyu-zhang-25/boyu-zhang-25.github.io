---
title: "Decoding Word Sense with Graphical Embeddings"
excerpt: "Implemented three deep graph encoders over WordNet for word sense embeddings bounded by hypernyms-hyponyms and meronyms-holonyms: a child-sum graph bi-LSTM, a matrix decomposition method with graph kernels, and a GCN.<br/><img src='/images/wsd.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

# Decoding Word Sense with Graphical Embeddings

By [Prof. Aaron Steven White](http://aaronstevenwhite.io/) and me :)

[The Formal And CompuTational Semantics lab (FACTS.lab)](http://factslab.io/)

University of Rochester, Fall 2019

# Result Visualization

## Graph bi-LSTM over the WN (depth = 3)
![genus](https://github.com/cristianoBY/Decoding-Word-Sense/blob/master/figures/tSNE_hidden_hyper_hypon_genus__n__02)

![instrumentality](https://github.com/cristianoBY/Decoding-Word-Sense/blob/master/figures/tSNE_hidden_hyper_hypon_instrumentality__n__03)

![person](https://github.com/cristianoBY/Decoding-Word-Sense/blob/master/figures/tSNE_hidden_hyper_hypon_person__n__01)

![worker](https://github.com/cristianoBY/Decoding-Word-Sense/blob/master/figures/tSNE_hidden_hyper_hypon_worker__n__01)
