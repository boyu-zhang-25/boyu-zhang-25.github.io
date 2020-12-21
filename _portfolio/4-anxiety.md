---
title: "Individual-level Anxiety Detection and Prediction from Longitudinal YouTube and Google Search Engagement Logs"
excerpt: "In this work, we propose an alternative method to identify individuals with anxiety and further estimate their anxiety levels using personal online activity histories from YouTube and the Google Search engine, platforms that are used by millions of people daily.

	>Pervasive Computing; Mental Health.


<img src='/images/anxiety.png'>"
collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->


<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
>Pervasive Computing; Mental Health.

- Anxiety disorder is one of the world's most prevalent mental health conditions, arising from complex interactions of biological and environmental factors and severely interfering with one's ability to lead normal life activities. Current methods for detecting anxiety heavily rely on in-person interviews, which can be expensive, time-consuming, and blocked by social stigmas.

- In this work, we propose an alternative method to identify individuals with anxiety and further estimate their anxiety levels using personal online activity histories from YouTube and the Google Search engine, platforms that are used by millions of people daily. We ran a longitudinal study and collected multiple rounds of anonymized YouTube and Google Search logs from volunteering participants, along with their clinically validated ground-truth anxiety assessment scores. We then developed explainable features that capture both the temporal and contextual aspects of online behaviors. 

- Using those, we were able to train models that 
	1. identify individuals having anxiety disorder with an average F1 score of $0.83 \pm 0.09$.
	2. assess the level of anxiety by predicting the gold standard Generalized Anxiety Disorder 7-item scores (ranges from $0$ to $21$) with an MSE of $1.87 \pm 0.14$ based on the ubiquitous individual-level online engagement data. 

- Our proposed anxiety assessment framework is cost-effective, time-saving, scalable. It opens the door for it to be deployed in real-world clinical settings, empowering care providers and therapists to learn about anxiety disorders of patients non-invasively at any moment in time.

- **My Contribution**: I was the second author of this paper. In a team of two, I first collected longitudinal private Google Search and YouTube history from volunteer participants via the Google Takeout platform. The pipeline and data storage are cloud-based, HIPAA-compliant, and vetted by the IRB, prioritizing the privacy and security of the participants. In collaboration with the University of Rochester Medical Center, we have recruited more than 200 patients and college student volunteers, periodically collecting their clinically validated mental health evaluation results and observing their longitudinal behavior changes. 

	For the experiments, I extracted a set of explainable features that captures the temporal and semantic signals in personal online history logs: a novel representation of activity intervals based on self-exciting point processes, entropies for time and online content diversity, and inactivity periods. These features are later shown to be strong indicators in detecting anxiety symptoms. In addition, I customized a Gaussian Process that can continually predict individual anxiety levels in the future. This setup may have a potential impact on the assistance delivery system: counselors can use the model weekly to monitor the anxiety levels of patients remotely *in-between* sessions, obtaining a more comprehensive patient profile.<br/><img src='/images/anxiety.png'>

- Please see our paper [here](https://arxiv.org/pdf/2007.00613.pdf).  

