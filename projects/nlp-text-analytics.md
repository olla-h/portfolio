# NLP — Semantic Regulation Detection in Banking

## Overview

A research project focused on using Natural Language Processing (NLP) and
semantic analysis to automate the detection of banking regulations.

This work was conducted as part of the research paper:

> Dehkharghani, R., Hussein, O., Can, E., Oryngaliyeva, L., & Kantaş, H.
> (2025). "A Semantic Approach to Regulation Detection in Banking Domain."
> *Kamu Yönetimi ve Teknoloji Dergisi*, 7(2), 192–208.

The paper was published on July 31, 2025.  
[Read the published paper](https://dergipark.org.tr/en/pub/kaytek/article/1763869)

## Problem

Monitoring whether banking regulations are reflected in existing regulatory
documents can require substantial manual effort.

The project investigated a semantic NLP approach for identifying potentially
relevant and newly introduced regulations within a large collection of
regulatory documents.

## My Contribution

I contributed to the development and implementation of the NLP-based
semantic analysis approach used in the research.

My work involved:

- Natural language preprocessing
- Turkish-language text processing
- Keyword extraction using YAKE
- Semantic text representation
- Sentence-transformer-based semantic analysis
- BERT-based language representation
- Similarity-based regulation detection
- Dataset preparation and processing
- Evaluation of the proposed approach
- Analysis and interpretation of the results
- Research documentation and paper preparation

## Approach

The system combined keyword extraction and semantic representations to
identify regulations within a large collection of regulatory documents.

### Pipeline

Regulatory Documents
        ↓
Text Preprocessing
        ↓
YAKE Keyword Extraction
        ↓
BERT / Sentence-Transformer Representations
        ↓
Semantic Analysis
        ↓
Regulation Detection
        ↓
Expert Validation
        ↓
Semi-Automated Regulatory Monitoring

## Data

The system worked with two main sources of text:

- A large collection of regulatory documents published by the Banking
  Regulation and Supervision Agency (BDDK)
- A target set of regulations provided by a Turkish bank

The combination allowed the system to compare regulatory content and identify
potentially relevant/new regulations.

## Technologies & Methods

### NLP

- Natural Language Processing
- Text preprocessing
- Keyword extraction
- Semantic similarity
- Sentence embeddings

### Models & Libraries

- BERT
- Sentence Transformers
- YAKE
- Python

## Results

The proposed approach achieved:

- **86% Precision**
- **89% Recall**

for the regulation detection task.

The system was designed as a **semi-automated approach**, allowing an expert
to review and validate the regulations identified by the system.

## Research Publication

**Dehkharghani, R., Hussein, O., Can, E., Oryngaliyeva, L., & Kantaş, H.
(2025).** "A Semantic Approach to Regulation Detection in Banking Domain."
*Kamu Yönetimi ve Teknoloji Dergisi*, 7(2), 192–208.

**Published:** July 31, 2025

**Role:** Co-author / NLP Research Contributor

[View the publication on DergiPark](https://dergipark.org.tr/en/pub/kaytek/article/1763869)

## Skills Demonstrated

- Natural Language Processing
- Turkish NLP
- BERT
- Sentence Transformers
- Semantic Analysis
- Keyword Extraction
- Text Similarity
- Machine Learning
- Data Preparation
- Research & Experimental Design
- Technical Documentation
- Academic Research
