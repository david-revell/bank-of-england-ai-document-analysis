# Bank of England: AI Document Analysis

This repository contains the final deliverables for a data science project completed as part of the University of Cambridge Data Science Career Accelerator. The project was developed for the Bank of England and presented to their data scientists. It focuses on the automated analysis of company earnings documents using AI techniques.

### Project Overview

We built a custom retrieval and evaluation pipeline for answering questions over Bank of England earnings transcripts. Key techniques include:

- Document chunking and semantic retrieval
- Similarity threshold tuning and filtering
- Evaluation using RAGAS metrics: **context_precision** and **context_recall**
- Scripting for scalable testing and visualisation

### Repository Contents

- `notebook/`: Main evaluation notebooks  
- `data/` and `Data/`: Questions and transcripts  
- `results_rag_retrieval/`: Outputs for different thresholds  
- `visuals/`: Supporting figures (e.g. histogram)  
- `ragas_builder.py`: Automated evaluation script  
- `process_graph.py`: Query engine using Neo4j  
