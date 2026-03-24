# Multimodal-End-to-End-Content-Based-Music-Recommendation-System 

## Overview [![Notebook](https://img.shields.io/badge/Report-PDF-blue?style=flat-square)](https://github.com/seoyeon3/Multimodal-End-to-End-Content-Based-Music-Recommendation-System/blob/main/Park_2025_Master_Thesis.pdf)
The rapid growth of music streaming platforms has greatly increased access to music, while also leading to more diverse and personalized listening preferences. However, this abundance of choice makes it increasingly difficult to discover content that truly aligns with individual tastes, highlighting the need for effective recommendation systems.

To address this, I focus on building personalized recommendation models that go beyond generic suggestions and better capture individual listening patterns. The model aims to build a recommender system that provides personalized matching tracks based on past playlist history.


## Methodology 

The model is built using deep learning techniques, including neural encoders and cross-attention mechanisms, to learn rich representations of both users and items. Instead of learning user and item embeddings separately, the model adopts an end-to-end training approach where both embeddings are learned jointly and continuously updated based on their interactions.

As a multi-modal content-based system, the model integrates multiple sources of information, including audio features and textual metadata such as track and album names, to better represent the characteristics of music.
