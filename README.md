# Research_data_supplychainresilience
This repository contains the code and sample data used in the research project: Navigating Turbulence with Large Language Models and Neural Networks: A Machine Learning Approach to Predicting Resilience across Global Automotive Supply Networks.
- `Resi_LLM_model.py`: Python script that implements the Resi-LLM model. The model integrates graph-based network features and LLM-derived textual features to predict resilience scores using Multilayer perceptron model.
- `sampledata.csv`: A sample dataset containing 20 example entries. Each entry includes:
  - A target column representing the resilience score (`Y`)
  - Four columns of network structural features (e.g., nodes tiers, degree centrality, community, and out/in-degree ratio)
  - 1536 columns of LLM-based textual embeddings
