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
> PHROGs averaged embeddings figures present in https://console.cloud.google.com/storage/browser/plm-model-comparison/phrog-embedding-figures

##  Trained Model Performances on PHROGs: 
### Necessary Files: 
* splits_01092023.pkl present in https://storage.googleapis.com/plm-model-comparison/phrog-performance-files/splits_01092023.pkl
### Code and Data Availability: 
Code for training the functional classifiers and creating the precision, recall and F1 boxplots are present in the directory *phrog-performance*
> PHROGs functional classifier data present under *5CV_LMs_performance* in each model directory

##  Trained Model Performances on EFAM: 
### Necessary Files: 
* Final_Super_Condensed_Annotations-updated_efam.tsv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/Final_Super_Condensed_Annotations-updated_efam.tsv
* efam_phrog_e10.csv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/efam_phrog_e10.csv
* PHROG_index_revised_v4_10292022.csv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/PHROG_index_revised_v4_10292022.csv
* dereplicated_filtered_proteins_efam_downloaded_10162022.faa present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/dereplicated_filtered_proteins_efam_downloaded_10162022.faa
* efam_cluster_average_protein_length.csv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/efam_cluster_average_protein_length.csv
### Code and Data Availability: 
Code for training the functional classifiers and testing their performances on EFAM are present in the directory *efam-performance*
> PHROGs trained classifiers present in https://console.cloud.google.com/storage/browser/plm-model-comparison in their respective folders, labeled models
