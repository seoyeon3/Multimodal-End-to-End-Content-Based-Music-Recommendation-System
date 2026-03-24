# Multimodal End-to-End Content Based Music Recommendation System 

## Overview [![Thesis](https://img.shields.io/badge/Thesis-Master%20PDF-8A2BE2?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://github.com/seoyeon3/Multimodal-End-to-End-Content-Based-Music-Recommendation-System/blob/main/Park_2025_Master_Thesis.pdf)

The rapid growth of music streaming platforms has greatly increased access to music, while also leading to more diverse and personalized listening preferences. However, this abundance of choice makes it increasingly difficult to discover content that truly aligns with individual tastes, highlighting the need for effective recommendation systems.

To address this, I focus on building personalized recommendation models that go beyond generic suggestions and better capture individual listening patterns. The model aims to build a recommender system that provides personalized matching tracks based on past playlist history.


## Methodology 

The model is built using deep learning techniques, including neural encoders and cross-attention mechanisms, to learn rich representations of both users and items. Instead of learning user and item embeddings separately, the model adopts an end-to-end training approach where both embeddings are learned jointly and continuously updated based on their interactions.

As a multi-modal content-based system, the model integrates multiple sources of information, including audio features and textual metadata such as track and album names, to better represent the characteristics of music.


## Project Workflow

The project follows a structured pipeline for building the recommendation system:

1. **Data Collection**  
   - [`1_spotify_api_data_collection.ipynb`](./1_spotify_api_data_collection.ipynb)  
   - Collected music data using Spotify API  

2. **Positive / Negative Sampling**  
   - [`2_positive_negative_sampling.ipynb`](./2_positive_negative_sampling.ipynb)  
   - Generated training samples (I+, I−) based on playlist interactions  

3. **Text Embedding (BERT)**  
   - [`3_bert_embedding_generation.ipynb`](./3_bert_embedding_generation.ipynb)  
   - Converted track and album names into contextual embeddings  

4. **Model Training (Multi-modal + Cross-Attention)**  
   - [`4_cross_attention_multimodal_example.ipynb`](./4_cross_attention_multimodal_example.ipynb)  
   - Trained the end-to-end recommendation model using audio features and textual metadata (track and album names)


This repository provides a reference implementation for project.  
For full experimental results and detailed analysis, please refer to the thesis.
