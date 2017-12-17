---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech. in Computer science, Sri Venkateswara University, 2013
* M.S. in Computer science, Indiana University Bloomington, 2019 (expected)

Work experience
======
* Fall 2017: Graduate Research Assistant
  * Indiana University Bloomington
  * Duties included: Worked on edge computing IoT platform, integrated streaming data(CoAP protocol) from edge devices with Apache heron and performed machine learning alogrithms on it. Built complex topologies on Apache heron for efficient data processing in Heron.
  * Supervisor: Professor Martin Swany

* 2015-2017: Data Scientist
  * SAP
  * Duties included: Researched extensively on various machine learning algorithms for recommender systems, implemented random walk based approximation algorithm in apache spark. Market segmentation using supervised version of clustering algorithms, built micro services on top of cloud foundry using java. Automated deployment process using groovy scripts on jenkins.
  * Supervisor: Sheik Bilal

* 2013-2015: Associate Softwar Engineer
  * Accenture
  * Duties included: Built Auto scaling infrastructure based using chef opscode using ruby.Built Java based web services 
  
Skills
======
* Machine learning
  * Exploratory data analysis
  * Recommender systems using collaborative filtering
  * clustering algorithms
  * Regularized classfication and regression algorithms(Lasso,Ridge, ElasticNet)
  * Ensemble learning using boosting algorithms(XGBoost)
  * Convolutional neural networks
* Data Mining
  * Association rule minig techniques(FPGrowth, Apriori, KORD)
  * Random walk based approximation algorithms
  * Named entity recognition using stanfordnlp
* Distributed Systems
  * Apache Spark
  * Apache Heron
  * Apache Hadoop
* Programming Languages
  * Java
  * Python
  * SQL
  * C
* Predictive Analytics
  * SAP Lumira
  * PredictionIO
* Container technologies
  * Docker
  * Kubernetes

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently part of 2 github organizations involving efficient routing algorithms for networks
