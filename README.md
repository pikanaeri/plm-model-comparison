# plm-model-comparison
Comparing novel Protein Language Models

The procedures below are heavily based off of the procedures in https://www.nature.com/articles/s41564-023-01584-8. 

PHROGs annotation table:
> .tsv: https://storage.googleapis.com/plm-model-comparison/PHROG_index.tsv
> 
> .csv: https://storage.googleapis.com/plm-model-comparison/EFAM_embed/PHROG_index.csv


## PHROG Embedding: 
### Necessary Files: 
* The PHROGs annotation table (.tsv format)
* PHROGs fasta files are present in https://github.com/pikanaeri/Extracting-3Di-Embeddings-from-Protein-Sequences/tree/main/FAA_phrog; files can also be found under the Fasta Files category at https://phrogs.lmge.uca.fr/
### Code and Data Availability: 
Code for extracting the embeddings for each model is present in the directory *extracting-embeddings*
> PHROGs model embeddings and final averaged embeddings present in https://console.cloud.google.com/storage/browser/plm-model-comparison in folders, labeled final_embeddings and final_average_embeddings respectively

Code for creating the embedding figures for each model is present in the directory *phrog-embedding-figures*
> PHROGS averaged embeddings figures present in https://console.cloud.google.com/storage/browser/plm-model-comparison/phrog-embedding-figures

##  Trained Model Performances on PHROGs: 
### Necessary Files: 
* splits_01092023.pkl present in https://storage.googleapis.com/plm-model-comparison/phrog-performance-files/splits_01092023.pkl
### Code and Data Availability: 
Code for training the PHROGs classifier and calculating the precision, recall and F1 scores for each model are present in the directory *phrog-performance*
> PHROGs trained models present in https://console.cloud.google.com/storage/browser/plm-model-comparison in their respective folders, labeled models

##  Trained Model Performances on EFAM: 
### Necessary Files: 
* Final_Super_Condensed_Annotations-updated_efam.tsv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/Final_Super_Condensed_Annotations-updated_efam.tsv
### Code and Data Availability: 
