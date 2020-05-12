---
layout: post
title:  BM25 Review Search
excerpt: There are numerous reviews available and it is not feasible to go through every one of them manually in order to obtain the information needed......
# categories: [HTML,Code]
---
There are numerous reviews available and it is not feasible to go through every one of them manually in order to obtain the information needed.

We have implemented a search engine using BM25 that will fetch the most relevant reviews to the given user query.

Okapi BM25 is a ranking function used to rank documents of the data set based on the relevance to a given query. It considers term frequency as well as document length. Given a query, it will assign a score to every document (review in this case). Larger score means the document is more relevant to the query, correspondingly, smaller score denotes less relevance.

We are fetching 5 most relevant reviews to the user query.
