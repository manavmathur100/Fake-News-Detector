![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/ba1bb104-cb4f-41c3-bd8c-1d53fcfc6a0f)# Fake-News-Detector

## Overview
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable. Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.

## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.

The intended application of the project is for use in applying visibility weights in social media. Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.

## Dataset Description
train.csv: A full training dataset with the following attributes:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable
test.csv: A testing training dataset with all the same attributes at train.csv without the label.

## Comparing Accuracies of Models
![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/8bee0a73-c645-46d0-b33c-d8f8d4c0294d)

## Confusion Matrices

Naive Bayes
![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/3750e7bd-793e-4cce-b0eb-f932a4ecfdab)

SVM
![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/52315e7e-2b52-4983-af8e-d7bf54a7ca7a)


Neural Network with TensorFlow

![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/25e17060-51c5-4698-87bc-5a00879ee75c)

Neural Network with Keras

![image](https://github.com/manavmathur100/Fake-News-Detector/assets/70790093/d939d501-4ecd-4a30-a96b-cbf740f017f4)




