# Biomedical-Parallel-Corpus

This repository contains biomedical domain data scraped from Wikipedia for the French-English language pair. We first scraped in-domain data and extracted parallel sentences using three similarity thresholds i.e. Threshold 90, 85, and 80 (as repo folders present their respective threshold). In this first development phase, we had three data files ( Threshold 90, 85, and 80). As this data had many out-domain sentences, we applied a second in-domain filter to this data with a focus on pertaining biomedical domain sentences. In this filter, we retrieved in-domain sentences based on their proximity with in-domain data (Medline titles) and again retrieved using three different thresholds: Threshold 20, 10, and 0. So we have three data files here against each threshold file (developed at the first data collection phase) i.e. 

Threshold90: biofiltered t20,t10, and t0.

Threshold85: biofiltered t20,t10, and t0.

Threshold80: biofiltered t20,t10, and t0.


#Cite us:
If you use our corpus, kindly cite our [paper](https://aclanthology.org/2023.wmt-1.26/):



