---
title: "Individual-level Anxiety Detection and Prediction from Longitudinal YouTube and Google Search Engagement Logs"
excerpt: "In this work, we propose an alternative method to identify individuals with anxiety and further estimate their levels of anxiety using personal online activity histories from YouTube and the Google Search engine, platforms that are used by millions of people daily.
<!-- <br/><img src='/images/dpp-pruning.png' width='500' height='300'>" -->
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->

- Anxiety disorder is one of the world's most prevalent mental health conditions, arising from complex interactions of biological and environmental factors and severely interfering one's ability to lead normal life activities. Current methods for detecting anxiety heavily rely on in-person interviews, which can be expensive, time-consuming, and blocked by social stigmas. 

- In this work, we propose an alternative method to identify individuals with anxiety and further estimate their levels of anxiety using personal online activity histories from YouTube and the Google Search engine, platforms that are used by millions of people daily. We ran a longitudinal study and collected multiple rounds of anonymized YouTube and Google Search logs from volunteering participants, along with their clinically validated ground-truth anxiety assessment scores. We then developed explainable features that capture both the temporal and contextual aspects of online behaviors. 

- Using those, we were able to train models that 
	1. identify individuals having anxiety disorder with an average F1 score of $0.83 \pm 0.09$.
	2. assess the level of anxiety by predicting the gold standard Generalized Anxiety Disorder 7-item scores (ranges from $0$ to $21$) with a MSE of $1.87 \pm 0.14$ based on the ubiquitous individual-level online engagement data. 

- Our proposed anxiety assessment framework is cost-effective, time-saving, scalable, and opens the door for it to be deployed in real-world clinical settings, empowering care providers and therapists to learn about anxiety disorders of patients non-invasively at any moment in time.

- Please see our paper [here](https://arxiv.org/pdf/2007.00613.pdf).  

