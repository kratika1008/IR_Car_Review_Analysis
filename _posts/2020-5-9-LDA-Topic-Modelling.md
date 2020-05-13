---
layout: post
title: LDA Topic Modelling
#categories: Miscellaneous
excerpt: We used LDA Multicore and LDA Mallet from genism library to generate topics......

---

We used LDA Multicore and LDA Mallet from genism library to generate topics.
Observation: LDA Mallet performed significantly faster, however in our case, we got better results with LDA multicore. The topics were well separated.
### Visualization of topics
We pyLDAvis , python version of LDAvis. We make use of the relevance score metric(lambda) which was designed by the authors of https://nlp.stanford.edu/events/illvi2014/papers/sievert-illvi2014.pdf  - Kenneth Shirley and Carson Sievert respectively. The visualization uses a metric called relevance (lambda). This tells us how relevant each word is for a topic.

### Evaluation of the topics
Coherence score is basically a statistic which measures the semantic similarity between the high scoring words within the topic.

We use coherence score to find out the optimal value of number of topics to be used. Based on coherence score, we found 8 topics was ideal.

<a href="../lda_8_topics.html">LDA Results</a>
