---
title: "Aggregating Search Logs and Self-esteem for Identifying Individuals with History of Suicide Ideation"
excerpt: "A Bayesian graphical model that incorporates the latent interdependence between self-esteem, quotidian cognitive states, and online engagements to identify past suicide ideation.<br/><img src='/images/psi.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

- We propose a framework for identifying individuals with a history of suicide ideation from their daily online search logs. A total of $1,043,855$ searches were collected from $120$ college students, with an average of $10926$ searches per participant, spanning over $4.21$ years of search history. The participants also filled out a gold-standard mental health assessment survey. 

- To detect the history of suicide ideation, we first examined both semantic search content category features and temporal recurrence and frequency features. Using those features, we develop a novel encoding that projects these aspects of search behaviors into a low dimensional vector space. Our supervised model incorporates both in-the-moment online behaviors and the ground truth self-esteem for identifying individuals with a history of suicide ideation and verifies the hypothesis that including self-esteem, during modeling, improves the suicide ideation detection task. 

- Labels for the training and testing sets were drawn from professional mental health surveys. Our highest-performing graphical model achieved a classification F1 score of $0.83$ with an AUC of $0.81$ on a stratified test set population. Our framework of leveraging passively sensed search data could help caregivers and practitioners to identify individuals with a potential history of suicide ideation and extend help.

