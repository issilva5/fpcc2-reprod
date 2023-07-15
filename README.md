# Applying Zero-Shot Next-Item Recommendation for Music Recommendation in the LastFM dataset

This repository holds the scripts and data used in the reproduction of the replication of the  [Zero-Shot Next-Item Recommendation using Large Pretrained Language Models](https://arxiv.org/abs/2304.03153) paper.

The files are organized as follows:

 1. **data**: contains the train, validation, test and metadata datasets, as well the json input and output of the NIR script.
 2. **models_logs**: contains the log files for each model (POP, FPMC, GRU4Rec, SASRec, NIR). In the logs we can found the information about the models performance.
 3. **scripts**: contains the LastFM pre-processing scripts in the form a Python Notebook and the NIR script based on the original one found [here](https://github.com/AGI-Edgerunners/LLM-Next-Item-Rec).