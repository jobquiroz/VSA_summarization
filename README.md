# VSA_summarization
Using VSAs to summarize texts

This repository contains the notebooks for the in-review article "Using pretrained word embeddings to create hyperdimensional computing representations".

In this work we present a method for adjusting pretrained embeddings to a goal context. We map word embeddings to a high-dimensional binary space where the properties of Hyperdimensional Computing apply. 
To test the effectiveness of this solution we use this mapping to summarize texts. 

This repository contains the following notebooks and directories:

- HDComputing_basics.ipynb: It implements the most basic functions defined in Hyperdimensional Computing
- Summarize_Texts.ipybn: It contains the whole process to create a summary, from representation to sentence selection
- Calling_summarize.ipynb: It calls the previous notebook to actually summarize a set of texts
- Texts/:  Contains the .txt files for the DUC 2002 dataset
- Summaries/: The final summaries as .txt files
- Precalc_distances/: Used for saving time when doing several experiments with Calling_summarize.ipynb


All notebooks mainly use standard Python 3 libraries except for Spacy (https://spacy.io/).
We use the pretrained model *'en_core_web_lg'*
