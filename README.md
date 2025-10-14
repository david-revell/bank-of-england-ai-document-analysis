# Bank of England: AI Document Analysis  

This repository contains the final deliverables for a data science project completed as part of the University of Cambridge Data Science Career Accelerator. The project was developed for the Bank of England and presented to their data scientists. It focuses on the automated analysis of company earnings documents using AI techniques.

## Overview  

The project combined classical NLP and retrieval-augmented generation (RAG) methods to extract, classify, and query information from financial Q&A transcripts. Using Barclays and Citibank data, the system transforms unstructured dialogue into searchable, interpretable insights.  

## Methods  

- **Classical NLP pipeline:** Extracted structured question–answer pairs, identified topics using FinBERT + BERTopic, and analysed sentiment and emotion.  
- **Retrieval system:** Built a Neo4j graph linking facts to their document sources and implemented a RAG agent for interactive querying.  
- **Evaluation:** Measured retrieval quality using *context precision* and *context recall* from RAGAS, tuning similarity thresholds to balance coverage and noise.  
- **Interface:** A Streamlit dashboard visualised topic and sentiment trends and provided chatbot access to the underlying graph.  

## Results  

The combined workflow revealed clear thematic shifts and sentiment patterns across quarters, while retrieval tests confirmed accurate, explainable document grounding. Together these tools illustrate a scalable AI approach for monitoring financial narratives.  
