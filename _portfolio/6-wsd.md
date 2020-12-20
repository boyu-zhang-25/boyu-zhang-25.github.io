---
title: "Decoding Word Sense with Graphical Embeddings"
excerpt: "Implemented three deep graph encoders over WordNet for word sense embeddings bounded by hypernyms-hyponyms and meronyms-holonyms: a child-sum graph bi-LSTM, a matrix decomposition method with graph kernels, and a GCN.<br/><img src='/images/wsd.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

# Decoding Word Sense with Graphical Embeddings

This project was sponsored by the [Discover Grant](https://www.rochester.edu/college/ugresearch/funding/discover-grant/index.html) of Summer 2019 at the University of Rochester. 

I was supervised by [Prof. Aaron Steven White](http://aaronstevenwhite.io/) from the [Formal And CompuTational Semantics lab (FACTS.lab)](http://factslab.io/)


# Result Visualization

## Graph bi-LSTM over the WordNet (depth = 3)
<img src='/images/tSNE_hidden_hyper_hypon_genus__n__02.png' class='center'><br>
<img src='/images/tSNE_hidden_hyper_hypon_instrumentality__n__03.png' class='center'><br>
<img src='/images/tSNE_hidden_hyper_hypon_person__n__01.png' class='center'><br>
<img src='/images/tSNE_hidden_hyper_hypon_organism__n__01.png' class='center'><br>
<img src='/images/tSNE_hidden_hyper_hypon_worker__n__01.png' class='center'><br>


The code can be found [here](https://github.com/boyu-zhang-25/Decoding-Word-Sense).
