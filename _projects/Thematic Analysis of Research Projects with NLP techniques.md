---
layout: page
title: Thematic Analysis of Research Projects with NLP techniques
description: Implement a text pre-processing pipeline to optimize vector representations for machine learning tasks
img: assets/img/analysis_NLP/main.jpg
importance: 2
category: ML/AI
---

## Abstract

This project presents a data analysis and processing approach applied to European Commission-funded research projects within the Horizon 2020 program. Using a dataset of 35,378 project summaries, the project implements a text pre-processing pipeline to optimize vector representations for machine learning tasks using Python. Pre-processing includes text cleaning, tokenization, lemmatization, and stopword removal, followed by various vectorization techniques, including TF-IDF, Word2Vec, and transformer-based embeddings. Two regression methods—neural networks with PyTorch and Random Forest regression—were evaluated to predict publication and patent counts. Additional dataset features such as total cost and EU funding amount further enhance model accuracy. Though synonym augmentation with the WordNet thesaurus provided marginal gains, future work could explore integrating more project attributes. This work demonstrates a scalable pipeline for semantic analysis of large textual datasets, with potential applications in automated project evaluation and funding assessment.

This project was carried out in collaboration with [Oier Huici Itarte](https://oierhuici.github.io/) as part of Telecommunications Engineering Master's at UC3M.

The complete report can be found [here](https://edgomezg.github.io/assets/pdf/Analysis_NLP.pdf).

## GitHub Repository

You can find the code for this project along with the results and datasets on [GitHub](https://github.com/edgomezg/Thematic-Analysis-of-Research-Projects-with-NLP-techniques).
