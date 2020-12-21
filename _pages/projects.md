---
<!-- layout: archive -->
title: "Projects"
permalink: /projects/
author_profile: true
---
Will keep updating : )
## Can We Automate Scientific Reviewing?
<img src="/images/bot.png" width="100px" style="float: left">
<br>
[Github](https://github.com/neulab/ReviewAdvisor)<br>
<a href="https://yyy-apple.github.io/files/ReviewAdvisor.pdf" target="_blank">Paper</a><br>
[Demo](http://review.nlpedia.ai/)


**Dataset**: (1) Collected a dataset consisting of ICLR papers and NIPS papers together with their aligned reviews. (2) Defined an aspect typology that contains eight aspects for review structuralization. (3) Set up an interactive online annotation platform for crowd workers to annotate aspect information in reviews. (4) Used partial annotated reviews to train a sequence labeling model and annotated the whole dataset.<br>
**Evaluation**: (1) Summarized five most frequently mentioned desiderata for a good review. (2) Took the first step towards review evaluation by defining seven quantifiable metrics that can measure how well a review realizes those desiderata.<br>
**Model**: (1) Decomposed review generation into extractive and abstractive stages. (2) Investigated three different unsupervised summarization strategies in the extractive stage and two paradigms in the abstractive stage. (3) Extensively evaluated generated reviews from six systems as well as reference reviews and interpreted their relative merits based on our fine-grained evaluation metrics.<br>
**Fairness**: Proposed two ways to quantify bias in reviews, one measures absolute bias in a single system, the other measures relative bias between two systems.<br>


## Other course Projects
### Deep Reinforcement Learning and Control
Course Number: 10703 &emsp; Instructor: [Katerina Fragkiadaki](https://www.cs.cmu.edu/~katef/)<br>
1. Implemented Twin Delayed Deep Deterministic Policy Gradients (TD3) and used Model-Based Policy Optimization with probabilistic ensembles to help faster the learning process where interacting with the environment is expensive.
2. (1) Investigated four exploration methods for TD3 in a sparse-reward situation, which are action noise, time-correlated action noise, parameter space noise, random network distillation. (2) Analyzed their relative advantages and disadvantages.

### Neural Networks for NLP
Course Number: 11747 &emsp; Instructor: [Graham Neubig](http://www.phontron.com/)<br>
1. Implemented a text classifier using Convolutional Neural Network.
2. Re-implemented the state of the art abstractive summarization system on CNN/DM and achieved 44.23 ROUGE-1 score. 
3. Developed a novel aspect-summarization model using reinforcement learning with knowledge graph enhanced reward.

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
cache recently accessed web content.