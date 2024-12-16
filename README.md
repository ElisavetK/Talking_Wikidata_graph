# Talking_Wikidata_graph

This repository stores data and scripts for the analysis related to the paper "Talking Wikidata: Communication patterns and their impact on community engagement in collaborative knowledge graphs" (https://arxiv.org/abs/2407.18278).

## **Data** 
This folder includes code for gathering and processing the data of this thesis.
* **download_Wikidata_dumps**: This is a script to download Wikidata xml dumps from https://dumps.wikimedia.org/wikidatawiki/ .
* **process_dumps_for_discussions.py**: This is a script to process the xml files and extract discussion pages.
* **process_dumps_for_edit_history.py**: This is a script to process the xml files and extract the edit history of editors.
* **process_data_separate_threads.ipynb**: This notebook process the raw text to separate threads, posts, and then extract the username for each post.


The file **process_data.ipynb** consists of the analysis of processing the raw data to separate discussions and identify usernames. Furthermore, it includes the process of creating the editors' features.

The file **items_cleaned.csv.zip** includes the dataset of discussions found in item talk pages.

The directory **graph analysis** consists of the network analysis code and data.

The file **framework_analysis.ipynb** includes the code for the text and graph embeddings, and the neural network model.
