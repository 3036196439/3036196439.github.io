---
layout: post
title: "Literature Review Conclusion"
author: "Zhou Mozhe"
categories: journal
tags: [documentation,sample]
---
### Stock Market Analysis  
  
#### Introduction  
  
- The integration of sentiment analysis with stock prediction has significantly enhanced forecasting accuracy.  
- This approach complements traditional methods by incorporating textual information from various sources.  
  
#### Traditional Methods  
  
- Stock price prediction has traditionally relied on numerical OHCLP data.  
- Traditional machine learning (ML) methods like Support Vector Regression (SVR) have been extensively utilized.  
  
#### Deep Learning Revolution  
  
- The emergence of deep learning (DL) techniques has revolutionized stock market prediction.  
- DL techniques effectively capture intricate patterns and temporal dependencies within the data.  
- Examples of DL techniques include Long Short-Term Memory (LSTM), Recurrent Neural Networks (RNN), and Convolutional Neural Networks (CNN).  
  
#### Sentiment Analysis and Prediction Accuracy  
  
- Augmenting numerical data with sentiment analysis has become a growing trend to improve prediction accuracy.  
- Leveraging both news and market data can capture public mood and emotions, providing valuable insights into future market trends.  
- Studies analyzing finance-related tweets and news articles have found significant predictive power on subsequent stock movements.  
- By combining regression models and sentiment analysis, researchers have achieved improved prediction accuracy ranging from 89% to 97%.  
  
#### Comparative Analysis  
  
- Baseline models incorporating sentiment analysis often yield more accurate predictions compared to those relying solely on numerical data.  
- A study combining financial news titles, technical indicators, and sentiment analysis reported improved prediction accuracy for intraday directional movements of the Standard & Poor's 500 index.  
  
#### Integration of External Knowledge Sources  
  
- The integration of external knowledge sources, particularly knowledge graphs (KG), has emerged as a promising approach to enhance prediction accuracy.  
- KGs provide a rich repository of structured information that can complement sentiment analysis and numerical data, offering a more holistic view of the stock market.  
- Studies combining KG with news and fundamental stock information have reported improved prediction accuracy, demonstrating the potential of integrating diverse data sources in stock market forecasting.


### Knowledge Graphs (KG) 
  
#### Introduction
- Knowledge Graphs (KG): Fundamental structure for representing knowledge in a graphical format.  
- Entities and Relationships: Nodes represent entities or concepts, and edges represent their relationships.  
- Academic Research Applications: Organizing and interconnecting diverse types of scholarly data (research papers, authors, institutions, conferences, topical domains).  
- Key Approaches for Obtaining Embeddings from KGs are listed as below.
  
#### Entity Extraction with NER
- Named Entity Recognition (NER): Identification and categorization of critical entities in textual data (people, locations, organizations, temporal information).  
- Evolution of NER Techniques: Rule-based and statistical methods to deep learning-based approaches.  
- Significance: Cornerstone for NLP applications (question answering, text summarization, machine translation).  
#### KG Subgraph Construction

- Selective Extraction: Extraction of relevant entities and relationships from the larger KG.  
- Reduced Complexity and Improved Efficiency: Focuses on the most pertinent information for tasks like question answering, recommendation systems, semantic search.  
#### KG Embedding

- Vector Representations: Generation of vector representations for entities and relations while preserving structural and semantic connections.  
- Spatial-based and Machine Learning-based Approaches:  
    + Spatial Methods: Conceptualize relations as translational operations in vector space (e.g., TransE).  
    + Machine Learning Methods: Leverage neural networks or semantic matching techniques (e.g., DistMult, ComplEx).  
- Applications: Link prediction, entity classification tasks.  
#### KG Neighbor Embedding

- Contextual Information Encoding: Capturing relationships between entities to encode contextual information.  
- Neighbor Information Aggregation: Explicit aggregation of neighbor information through graph convolutions or attention-based methods (e.g., KGCN, GATs).  
- Significance: Advance the ability to extract and utilize contextual information from KGs effectively.

### Embedding Generation in Large Language Models (LLMs)  
  
#### Introduction  
  
- Large Language Models (LLMs) have significantly impacted natural language processing due to their high-quality text generation capabilities.  
- There is growing interest in using LLMs for generating embeddings, which are dense vector representations that encode semantic and syntactic information of text.  
- Embedding learning in LLMs has the potential to enhance various downstream tasks in NLP.  
  
#### Techniques for Embedding Generation in LLMs  
  
- **Unsupervised Methods**: Techniques like Word2Vec and GloVe learn embeddings without labeled data, relying on patterns and structures in text.  
- **Supervised Methods**: These approaches use labeled data to train LLMs for generating task-specific embeddings tailored for particular downstream tasks.  
- **Self-supervised Methods**: Exemplified by BERT and GPT series, these techniques leverage auxiliary tasks like masked language modeling or next sentence prediction to learn context-aware embeddings.  
  
#### Architectural Designs in Embedding Generation  
  
- Transformer-based architectures, introduced in "Attention is All You Need," have become the preferred choice due to their ability to model long-range dependencies and capture contextual information effectively.  
- Various modifications and extensions to the transformer architecture have been proposed to improve embedding generation performance, such as incorporating additional attention mechanisms or utilizing transformer encoders/decoders.  
  
#### Conclusion  
  
- Embedding generation in LLMs is a rapidly evolving field with significant potential for enhancing various NLP tasks.  
- Different techniques and architectural designs have been explored to generate high-quality embeddings that capture semantic and syntactic information effectively.  
- Future research directions include exploring more advanced techniques and architectures for embedding generation and evaluating their performance on diverse downstream tasks.