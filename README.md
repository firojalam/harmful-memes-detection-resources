# Automatic Harmful Memes Detection Resources
Resources (conference/journal publications, references to datasets) for harmful memes detection.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/firojalam/harmful-memes-detection-resources)
[![Last Commit](https://img.shields.io/github/last-commit/firojalam/harmful-memes-detection-resources)](https://github.com/firojalam/harmful-memes-detection-resources)
[![Contribution_welcome](https://img.shields.io/badge/Contributions-welcome-blue)](https://github.com/firojalam/harmful-memes-detection-resources/blob/main/contribute.md)

## Overview

This repo contains relevant resources Automatic Harmful Memes Detection. We list a comprehensive and up-to-date information for harmful meme detection.

- [Harmful Memes Detection](#task-definition)
- [Datasets](#datasets)
- [Models](#model)
- [Relevant Surveys](#relevant-surveys)
- [Current SOTA](#current-sota)
<!-- - [Shared Tasks](#shared-tasks) -->

## Task Definition

## Datasets

<!-- ## Shared Tasks -->

## Models

## Relevant Surveys

## Current SOTA

| Title                                                                                                                                                                                           | Types          | Task                                                         | Dataset                                                                                                                         | Task Type                                                                                                    | Approach                                                                             | AUC  | Acc  | F1                                                                                                                                                                               | Details                                                                                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ | ---- | ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Detecting Harmful Memes and Their Targets](https://aclanthology.org/2021.findings-acl.246.pdf)                                                                                                 | Harm           | Harmful vs Non-harmful                                       | HarMeme (Covid-19)                                                                                                              | B                                                                                                            | VisualBERT (Pretrained using MS COCO)                                                |      | 0.81 | 0.8                                                                                                                                                                              |                                                                                                                                                                                                    |
| | | Very harmful vs Partially-harmful vs Non-harmful |                                                                                                                                                | M   |           |                                                              | 0.74                                                                                                                            | 0.54                                                                                                         |
| | | Target Identification of Harmful Memes |                                                                                                                                                          | M |             |                                                              | 0.76                                                                                                                            | 0.66                                                                                                         |
| [MOMENTA: A Multimodal Framework for Detecting Harmful Memes and Their Targets](https://aclanthology.org/2021.findings-emnlp.379.pdf)                                                           | Harm           | Harmful vs Non-harmful                                       | Harm-C                                                                                                                          | B                                                                                                            | MOMENTA: CLIP, VGG-19, DistilBERT, Cross-modal attention fusion (CMAF)               |      | 0.84 | 0.83                                                                                                                                                                             |
| Very harmful vs Partially-harmful vs Non-harmful                                                                                                                                                | M              |                                                              | 0.77                                                                                                                            | 0.55                                                                                                         |
| Target Identification of Harmful Memes                                                                                                                                                          | M              |                                                              | 0.78                                                                                                                            | 0.7                                                                                                          |
| Harmful vs Non-harmful                                                                                                                                                                          | Harm-P         | B                                                            |                                                                                                                                 | 0.9                                                                                                          | 0.88                                                                                 |
| Very harmful vs Partially-harmful vs Non-harmful                                                                                                                                                | M              |                                                              | 0.87                                                                                                                            | 0.67                                                                                                         |
| Target Identification of Harmful Memes                                                                                                                                                          | M              |                                                              | 0.79                                                                                                                            | 0.69                                                                                                         |
| Racist or Sexist Meme? Classifying Memes beyond Hateful                                                                                                                                         | Hate           | Protected category (PC) identification                       | FBHM                                                                                                                            | ML                                                                                                           | CIMG<br>\+ CTXT<br>\+ LASER<br>\+ LaBSE                                              | 0.96 |      |                                                                                                                                                                                  |
| Detecting attack type (AT)                                                                                                                                                                      | ML             | 0.97                                                         |                                                                                                                                 |                                                                                                              |
| [](https://dl.acm.org/doi/10.1145/3447535.3462502)[“Subverting the Jewtocracy”: Online Antisemitism Detection Using Multimodal Deep Learning](https://dl.acm.org/doi/10.1145/3447535.3462502)   | Hate           | Antisemitic content detection                                | GAB                                                                                                                             | B                                                                                                            | MFAS                                                                                 |      | 0.91 |                                                                                                                                                                                  |
| Twitter                                                                                                                                                                                         |                | 0.71                                                         |                                                                                                                                 |
| Antisemitism category classification                                                                                                                                                            | GAB            | M                                                            |                                                                                                                                 | 0.67                                                                                                         |                                                                                      |
| Twitter                                                                                                                                                                                         |                | 0.68                                                         |                                                                                                                                 |
| [](https://ieeexplore.ieee.org/document/8925199)[Detecting Sexist MEME On The Web: A Study on Textual and Visual Cues](https://ieeexplore.ieee.org/document/8925199)                            | Hate           | Automatic detection of sexist memes.                         | The MEME                                                                                                                        | B                                                                                                            | Late fusion                                                                          |      |      | 0.76                                                                                                                                                                             | Multi-modal Late-fusion<br>Hand-crafted visual dec\\scriptiors used: Low-level greyscale, colored, photographic and semantic features.<br>Bag-of-words approached used as textual features.<br>SVM |
| Memes in the Wild: Assessing the Generalizability<br>of the Hateful Memes Challenge Dataset                                                                                                     | Hate           | Hateful Meme Detection                                       | FBHM                                                                                                                            | CLIP (Linear Probe)                                                                                          |                                                                                      |      | 0.56 |                                                                                                                                                                                  |
| Pinterest                                                                                                                                                                                       | B              |                                                              |                                                                                                                                 | 0.57                                                                                                         |
| [Hate Speech in Pixels: Detection of Offensive Memes towards Automatic Moderation](https://arxiv.org/abs/1910.02334)                                                                            | Hate           | Hateful Meme Detection                                       | Google                                                                                                                          | BERT, VGG-16, MLP                                                                                            |                                                                                      | 0.83 |      |
| [](https://arxiv.org/pdf/2108.06207.pdf)[Disentangling Hate in Online Memes](https://arxiv.org/pdf/2108.06207.pdf)                                                                              | Hate           | Hateful Meme Detection                                       | FBHM                                                                                                                            | B                                                                                                            | DisMultiHate (BERT, Faster-RCNN, Disentangled representations)                       | 0.83 | 0.76 |
| MultiOFF                                                                                                                                                                                        |                |                                                              | 0.65                                                                                                                            |
| [](https://arxiv.org/abs/1910.03814)[Exploring Hate Speech Detection in Multimodal Publications](https://arxiv.org/abs/1910.03814)                                                              | Hate           | Hatespech detection in multimodal publications               | MMHS150K                                                                                                                        | B                                                                                                            | FCM (Feature concatenation model), Inception-V3, LSTM                                | 0.73 | 0.68 | 0.70                                                                                                                                                                             |
| [](https://arxiv.org/abs/2106.11229)[AOMD: An Analogy-aware Approach to Offensive Meme Detection on Social Media](https://arxiv.org/abs/2106.11229)                                             | Offensive      | Offensive (analogy) meme detection                           | GAB                                                                                                                             | Analogy-aware Multi-modal Representation Learning (Faster<br>R-CNN, ResNet50, Glove-based LSTM, BERT)<br>MLP |                                                                                      | 0.69 | 0.56 |
| Reddit                                                                                                                                                                                          | B              |                                                              | 0.72                                                                                                                            | 0.49                                                                                                         |
| [](https://ieeexplore.ieee.org/document/9582340)[KnowMeme: A Knowledge-enriched Graph Neural Network Solution to Offensive Meme Detection](https://ieeexplore.ieee.org/document/9582340)        | Offensive      | Offensive meme detection                                     | Reddit                                                                                                                          | YOLO V4, ConceptNET, GNN                                                                                     |                                                                                      | 0.73 | 0.49 | Knowledge-aware Multimodal Entity Extraction (KMEE): YOLO V4<br>Knowledge-enriched Information Network Construction: ConceptNET<br>Supervised Offensive Meme Classification: GNN |
| GAB                                                                                                                                                                                             | B              |                                                              | 0.7                                                                                                                             | 0.55                                                                                                         |
| [](https://ieeexplore.ieee.org/document/9402406)[An approach to detect offence in Memes using Natural Language Processing(NLP) and Deep learning](https://ieeexplore.ieee.org/document/9402406) | Offensive      | Offensive meme detection                                     | Offensive + Intensity dataset                                                                                                   | CNN, FastText, LSTM - Sigmoid                                                                                |                                                                                      | 0.96 |      |                                                                                                                                                                                  |
| Offense intensity prediction                                                                                                                                                                    | M              | CNN, FastText, LSTM - Softmax                                |                                                                                                                                 | 1                                                                                                            |                                                                                      |
| [](https://aclanthology.org/2020.trac-1.6/)[Multimodal Meme Dataset (MultiOFF) for Identifying Offensive Content in Image and Text](https://aclanthology.org/2020.trac-1.6/)                    | Offensive      | Offensive content detection                                  | [MultiOFF](https://github.com/bharathichezhiyan/Multimodal-Meme-Classification-Identifying-Offensive-Content-in-Image-and-Text) | B                                                                                                            | Early fusion: Stacked LSTM/ BiLSTM/CNN-Text + VGG16                                  |      |      | 0.5                                                                                                                                                                              | Early fusion technique (Stacked LSTM/ BiLSTM/CNN-Text + VGG16)                                                                                                                                     |
| [Detecting Propaganda Techniques in Memes](https://aclanthology.org/2021.acl-long.516.pdf)                                                                                                      | Propaganda     | Detecting the type of propaganda techniques used<br>in memes | Facebook                                                                                                                        | VisualBERT (Pretrained using MS COCO)                                                                        |                                                                                      |      | 0.48 | micro F1                                                                                                                                                                         |
| [MinD at SemEval-2021 Task 6: Propaganda Detection using Transfer Learning and Multimodal Fusion](https://aclanthology.org/2021.semeval-1.150.pdf)                                              | Propaganda     | Propaganda technique detection (Unimodal: Text)              | Facebook                                                                                                                        | ML                                                                                                           | Ensemble: BERT, RoBERTa, XLNet, ALBERT, DistilBERT, DeBERTa, Embeddings, Char n-gram |      |      | 0.59                                                                                                                                                                             | micro F1, Team name: MinD                                                                                                                                                                          |
| [Volta at SemEval-2021 Task 6: Towards Detecting Persuasive Texts and Images using Textual and Multimodal Ensemble](https://aclanthology.org/2021.semeval-1.149.pdf)                            | Propaganda     | Propaganda technique and span detection (Unimodal: Text)     | Facebook                                                                                                                        | ML                                                                                                           | RoBERTa                                                                              |      |      | 0.48                                                                                                                                                                             | micro F1, Team name: Volta                                                                                                                                                                         |
| [Alpha at SemEval-2021 Task 6: Transformer Based Propaganda Classification](https://aclanthology.org/2021.semeval-1.8.pdf)                                                                      | Propaganda     | Propaganda technique detection (Multimodal: Meme)            | Facebook                                                                                                                        | ML                                                                                                           | RoBERTa, Embeddings                                                                  |      |      | 0.58                                                                                                                                                                             | micro F1, Team name: Alpha                                                                                                                                                                         |
| Detection of Cyberbullying Incidents on the Instagram Social Network                                                                                                                            | Cyber-bullying | Detecting incidents of cyber-bullying                        | Instagram                                                                                                                       | B                                                                                                            | SVD +(Unigram, 3-gram), kernelPCA+(meta data, image categories) + lin. SVM           |      | 0.87 |                                                                                                                                                                                  |                                                                                                                                                                                                    |
| [A Dataset for Troll Classification of TamilMemes](https://aclanthology.org/2020.wildre-1.2.pdf)                                                                                                | Cyber-bullying | Detecting Troll memes                                        | TamilMemes                                                                                                                      | B                                                                                                            | ResNET (Training: TamilMemes)                                                        |      |      | 0.52                                                                                                                                                                             | macro F1                                                                                                                                                                                           |
| ResNET (Training: TamilMemes + ImageNet)                                                                                                                                                        |                |                                                              | 0.52                                                                                                                            |
| MobileNet (Training: TamilMemes + ImageNet + Flickr1k)                                                                                                                                          |                |                                                              | 0.47                                                                                                                            |
| ResNET (Training: TamilMemes + ImageNet + Flickr30k)                                                                                                                                            |                |                                                              | 0.52                                                                                                                            |
| [Multimodal Sentiment Analysis To Explore the Structure of Emotions](https://arxiv.org/abs/1805.10205)                                                                                          | \-             | Multimodal emotiom detection                                 | Tumblr                                                                                                                          | M                                                                                                            | Early fusion: Inception V3, LSTM                                                     |      | 0.72 |                                                                                                                                                                                  |                                                                                                                                                                                                    |
| [Multimodal Classification for Analysing Social Media](https://arxiv.org/abs/1708.02099)                                                                                                        | Reddit         | Common space fusion: InceptionNet, fastText, SVM             |                                                                                                                                 | 0.87                                                                                                         | 0.85                                                                                 |      |
| Flickr                                                                                                                                                                                          |                | 0.93                                                         | 0.91                                                                                                                            |
