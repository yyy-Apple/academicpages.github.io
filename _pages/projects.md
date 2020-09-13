---
<!-- layout: archive -->
title: "Projects"
permalink: /projects/
author_profile: true
---
Will keep Updating : )
## Auto-review for Research Papers
<img width="800" height="322" src="/images/ar.jpg"/><br>
(Still under going...)<br>
Here is a preliminary [demo](http://lor.lti.cs.cmu.edu:9999/)
1. Collected a dataset consists of ICLR papers and NIPS papers together with their aligned reviews from [OpenReview](https://openreview.net) and [NIPS Proceedings](http://papers.nips.cc).
2. Defined a typology consists of seven aspects (*Motivation*, *Originality*, *Soundness*, *Substance*, *Replicability*, *Meaningful Comparison*, *Clarity*) following [ACL review guidance](https://acl2018.org/downloads/acl_2018_review_form.html) 
3. Developed an online annotation platform for review aspect annotation using [Doccano](https://github.com/doccano/doccano).
4. Used partial annotated data to train a sequence labeling model to annotate the whole dataest.
5. Adopted an extract-then-generate paradigm and developed three unsupervised extraction strategies: section-based extration, [Cross Entropy Method](https://www.springer.com/gp/book/9780387212401) extraction, hybrid extraction.
6. Investigated two generation paradigm: vanilla sequence to sequence, generate tokens and their aspect jointly.
7. Evaluated two generation paradigm using multiple metrics including semantic equivalence, linguistical diversity(unique n-gram ratio, n-gram distribution), aspect diversity.
8. Analyzed the aspect-enhanced model by tracing back to the place the model attends when generating that aspect.

## Other course Projects
### Neural Networks for NLP
Course Number: 11747 &emsp; Instructor: [Graham Neubig](http://www.phontron.com/)<br>
1. Implemented a text classifier using Convolutional Neural Network
2. Re-implemented the state of the art abstractive summarization system on CNN/DM and achieved 44.23 ROUGE-1 score. 
3. Developed a novel aspect-summarization model using reinforcement learning with knowledge graph enhanced reward

### Algorighms for NLP
Course Number: 11711 &emsp; Instructor: [Yulia Tsvetkov](https://www.cs.cmu.edu/~ytsvetko/)<br>
Some of the course projects:
1. Implemented a trigram language model using Kneser-Ney smoothing and achieved efficient storage using bit-packing trick to fully use the 64 bit size in a machine.
2. Built an array-based CKY parser for English and improved its performance by doing complex structural annotation for the training data set.
3. Implemented a word alignment model for English-French translation using Hidden Markov Chain and Expectation Maximization.

### Cloud Computing
Course Number: 15619 &emsp; Instructor: [Majd Sakr](http://www.cs.cmu.edu/~msakr/)<br>
Some of the course projects:
1. Processed a large Wikipedia dataset using MapReduce programming model and analyzed topic trends.
2. Designed a suitable policy to maintain the Quality of Service (QoS) of a web service and realized it through configuring and deploying Elastic Load Balancer and AutoScaling groups on AWS.
3. Implemented strong and eventual consistency models for a distributed key-value store.
4. Processed and analyzed a huge Twitter social graph with the PageRank algorithm using Spark.

### Computer Systems
Course Number: 15513 &emsp; Instructor: [Brian Railing](http://www.cs.cmu.edu/~bpr/)<br>
Some of the course projects:<br>
1. Implemented a cache simulator that simulates the behavior of a hardware cache
memory and optimized a small matrix transpose function using blocking.
2. Designed a general purpose dynamic storage allocator for C programs with both high
throughput and utilization. 
3. Developed a Linux shell program that supports job control and I/O redirection. 
4. Designed a proxy server which can deal with multiple concurrent connections and
cache recently accessed web content. Will Keep Updating, view the projects