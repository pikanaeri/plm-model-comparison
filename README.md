<style>
H1{color:Blue !important;}
H2{color:DarkOrange !important;}
p{color:Black !important;}
</style>

# plm-model-comparison
Comparing novel Protein Language Models

## Necessary Files: 
PHROGs annotation table:
> .tsv: https://storage.googleapis.com/plm-model-comparison/PHROG_index.tsv
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

## Trained Model Performances on PHROGs: 
### Necessary Files: 
### Code and Data Availability: 
PHROGs trained models present in https://console.cloud.google.com/storage/browser/plm-model-comparison in their respective folders, labeled models

## Trained Model Performances on EFAM: 
### Necessary Files: 
* Final_Super_Condensed_Annotations-updated_efam.tsv present in https://storage.googleapis.com/plm-model-comparison/EFAM_embed/Final_Super_Condensed_Annotations-updated_efam.tsv
### Code and Data Availability: 
