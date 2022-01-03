# Dense Passage Retriever 
The following project Aims to train DPR model with the following stepes:
- Prepair http://quac.ai/ dataset and put in in a format needed to train a DPR model.
- Prepair https://sharc-data.github.io/data.html dataset and put in a format needed to train a DPR model.
- train DPR model 

## Procedure to replicate 
 - Run Generating DPR formated data from quac data.ipynb to generate DPR formated quac data.
 - Run Generating DPR formated data from sharc data.ipynb to generate DPR formated sharc data.
 - Run Merging data.ipynb to Merge and preprocess both data sets for training.
 - Follow DPR_training.ipynb to train DPR(bert-based-uncased) 

## Dependancies
 - Python 3.6
 - Elasticsearch 7.16.2
 - Haystack 2.5.0
