# Extraction Experiment Details
The template code for extracting the embeddings from a model is stored in extraction-base.ipynb.
To extract embeddings from a new protein language model, download the extraction-base notebook and fill in the required areas. 

For all extraction experiments, virtual machines were created using the Google Cloud Compute Engine.
- The machine utilizes a single NVIDIA L4 GPU under the G2 series, with 16 vCPU, 8 cores and 64 GB of memory (g2-standard-16).
- The operating system was Deep Learning with Linux, and the version was Deep Learning VM with CUDA 11.8 M123. The boot disks are balanced persistent, with sizes of 100 GB each.
- The average runtime for each experiment was two to three days.  
Batch sizes of 1 were used. 

In each notebook, additional details about the maximum sequence size and type of model are enclosed. 
