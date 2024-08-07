# Falcon-Hackathon

This is an attempt at creating a Continuously Learning LLM. 
The LLM stores all the data it is ever given in an external data source and then uses Knowledge Graph technique to continuously organise, summarise and prioritise data, leading to superior inference.

## Jupyter Notebook
A dataset of Twitter Customer Service tweets was taken from Kaggle.

The Dataset was stored in an external Knowledge Base. Then a Knowledge Graph was generated fromt he data.
This Knowledge Graph was used to organise data.
The Summary of th graph was used to summarise data and get the most central nodes of the graph.

The original tweets were also converted to complete threads.

All these artifacts were pushed in a Vector DB, which was queried when prompting the Falcon 180B model.
