---
layout: post
title:  "Locality Sensitive Hashing (LSH)"
date:   2018-03-16 18:30:00 +0530
categories: talks
comments : True
---
# Talk on Locality-Sensitive Hashing by [Rameshwar Pratap](https://sites.google.com/site/prataprameshwaryadav/)

#### Date: 20th, March, 2018

#### Time: 5:00 pm

#### Venue: Room 134, Old Acad. Block, IIIT-Bangalore

### Abstract:

Recent technological advancements have led to the generation of huge amount of data over the web such as texts, images, audios, and videos. Needless to say that most of these datasets are high dimensional. Searching for similar data-objects in such massive and high dimensional datasets has become a fundamental subroutine in many applications like clustering, classification, nearest neighbours, ranking etc. However, due to the "curse of dimensionality" and scale of the dataset, a brute-force way to compute the similarity scores on such data sets is very expensive and at times impossible. Therefore, it is desired to investigate the algorithms for scalable similarity search.

In this talk, we will discuss the use of Locality Sensitive Hashing (LSH) -- a celebrated result by [Indyk and Motwani, STOC 1998](http://www.cs.princeton.edu/courses/archive/spr04/cos598B/bib/IndykM-curse.pdf) -- for sublinear time similarity search. LSH is a search framework, which works in a two-step way:
1) reducing data dimension, and then
2) grouping similar objects in the same bucket.

We will discuss in detail the LSH for set representation of the dataset, and for Jaccard similarity, which is popularly known as ["Minwise-Independent-Permutations" by Broder et al., STOC 1998](https://dl.acm.org/citation.cfm?id=276781).

### About the Speaker:
Rameshwar has earned PhD in Theoretical Computer Science from Chennai Mathematical Institute. Post that he has worked with TCS Innovation Labs as a Research Scientist and with IIIT Bangalore as a Research Associate. Currently, he is working as a Principal Researcher in the areas of AI and Machine Learning. His research interest includes AI, Machine Learning, Data Science, Data Mining. In particular, he is interested in building scalable algorithms for massive datasets which offer a provable performance guarantee.

Link to the [slides](/pdfs/lsh-rameshwar.pdf).
## Other References for LSH:
Below are some useful links and other reference related to LSH (given by Rameshwar)

### Major Theoretical results
1. [Broder et. al., 1998](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.69.794&rep=rep1&type=pdf) LSH for Jaccard similarity over sets
2. [Charikar, 2002](https://www.cs.princeton.edu/courses/archive/spr04/cos598B/bib/CharikarEstim.pdf) LSH for Cosine similarity over real-valued vectors
3. [Gionis et. al., 1999](http://www.vldb.org/conf/1999/P49.pdf) LSH for Hamming distance over binary data
4. [Indyk and Motwani, 1998](http://www.cs.princeton.edu/courses/archive/spr04/cos598B/bib/IndykM-curse.pdf) LSH for Euclidean distance over real-valued vectors

### Applications of LSH ###
1. [Deduplication of text data](http://cs.brown.edu/courses/cs253/papers/nearduplicate.pdf)
2. [Finding Near-Duplicate Web Pages](https://infoscience.epfl.ch/record/99373/files/Henzinger06.pdf)
3. [Image search](https://www.robots.ox.ac.uk/~vgg/rg/papers/klsh.pdf)
4. [Scaling up deep learning performance](https://arxiv.org/pdf/1602.08194.pdf)

A [webpage](http://www.mit.edu/~andoni/LSH/) on the recent development in LSH, maintained by [Alex Andoni](http://www.mit.edu/~andoni/).
