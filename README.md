# Talking_Wikidata_graph

This repository stores data and scripts for the analysis related to the paper "Talking Wikidata: Communication patterns and their impact on community engagement in collaborative knowledge graphs" (https://arxiv.org/abs/2407.18278).

## **Data** 
This folder includes code for gathering and processing the data of this study.
* **download_Wikidata_dumps**: This is a script to download Wikidata xml dumps from https://dumps.wikimedia.org/wikidatawiki/ .
* **process_dumps_for_discussions.py**: This is a script to process the xml files and extract discussion pages.
* **process_dumps_for_edit_history.py**: This is a script to process the xml files and extract the edit history of editors.

## **Process raw data**
The file **process_data.ipynb** consists of the analysis of processing the raw data to separate discussions and identify usernames. Furthermore, it includes the process of creating the editors' features.

## **Dataset**
The file **items_cleaned.csv.zip** includes the dataset of discussions found in item talk pages.

## **Graph analysis**
This folder includes code for the network analysis.
* **graph_analysis.ipynb**: This notebook consists of the network analysis code.
* **statistics_data.ipynb**: This notebook includes statistical analysis and figures for the editors' features.
* **process_editor_features.ipynb**: This notebook presents the code for editors' features.


## **ML model**
The file **framework_analysis.ipynb** includes the code for the text and graph embeddings, and the neural network model.
