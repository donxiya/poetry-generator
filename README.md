# Project Introduction

Recent advances in natural language processing have enabled deeper exploration of emotional expression in poetry. For instance, the PO-EMO dataset introduced by Haider et al. (2020) focuses on aesthetic emotions in English and German poetry, using transformer-based models to identify nuanced emotional responses such as nostalgia or serenity rather than basic sentiment classes. Similarly, other studies have demonstrated the effectiveness of fine-tuning BERT-like models on emotion-tagged English poems, achieving strong classification performance across categories like joy, anger, and sadness (Kumar & Srinivasan, 2022). These findings highlight the feasibility of applying deep learning methods—especially transformer architectures—to complex emotional inference tasks in poetic language.

This project focuses on the classification and generation of English poems based on their textual content and emotional context. Using the Poetry Foundation Emotion-Annotated Dataset from Kaggle (source), which consists of poems scraped from the Poetry Foundation website, the dataset contains four key attributes: Title, Poem, Poet, and Genre. The Genre column represents an emotion-based classification derived by applying a fine-tuned BERT model that annotates the poems with emotion labels.

The primary goal of this project is to build a robust classifier capable of accurately categorizing poems into their corresponding emotional genres based on the text content. Beyond classification, the ultimate aim is to develop a generative model that can create new poems conditioned on specific words or emotional genres, thereby blending natural language understanding with creative text generation.

This work combines classical machine learning techniques, deep learning architectures such as BERT, and natural language processing methods to analyze and generate poetry, contributing to the intersection of computational creativity and emotion-aware language modeling.

# Citation:

Haider, T., Boleda, G., & Zampieri, M. (2020). PO-EMO: Conceptualizing and Annotating Aesthetic Emotions in Poetry. arXiv preprint arXiv:2009.10885. https://arxiv.org/abs/2009.10885

Kumar, R., & Srinivasan, P. (2022). Emotion Detection in Poetry using Transformer-based Models. Proceedings of the ACL Workshop on Computational Approaches to Literature.

Ekhaldi, A. (2022). English Poem Dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/abdelrahmanekhaldi/english-poem-dataset
