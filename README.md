# KnowledgeGraph_metaData
This repository the preserves meta data in knowledge graph.

Now auto-update function is available. 

Corresponding shell file is saved in aliyun server.

# Directory

The meta data of datasets, models(papers) and reimplement records are saved in yaml files. Please pay attention to the file format when uploading meta data.

## DatasetLogos

Storing logo pictures of dataset. All pictures are `.png` or `.jpg` file.

## dataset

Storing meta data of dataset.
Naming format: `d_[dataset name]_[uploader name]_[upload time(year)].yaml`

## model

Storing meta data of models or papers.
Naming format: `p_[paper title]_[Conference/Journal Abbreviation (all uppercase)]_[publish time(year)].yaml`

## reimplement

Storing data of models' reimplement results.
Naming format: `r_[paper title]_[uploader name]_[update time(year)].yaml`