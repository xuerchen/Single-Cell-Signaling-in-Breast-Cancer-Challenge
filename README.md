# Single-Cell-Signaling-in-Breast-Cancer-Challenge

This repo contain's our team Ostar's solution of [Single Cell Signaling in Breast Cancer Challenge
](https://www.synapse.org/#!Synapse:syn20366914/wiki/593925). 
We designed a transformer encoder neural network that jointly learns the sequential pattern of all the missing single cell markers by utilizing the self-attention mechanism. We are the only team in top 10 which submits a single model rather than a big ensemble.

To reproduce our results, please run the following notebooks in order:
- subchallenge_1_prepare_miao.ipynb
- subchallenge_1_prepare_rnn_miao.ipynb
- subchallenge_1_fastai_transformer.ipynb

We use dask multi gpu for data processing and analysis to get insights. Please run the following notebook:
- dask_data_processing.ipynb

Dependencies will be updated later.
