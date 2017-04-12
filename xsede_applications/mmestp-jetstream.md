Applicaiton by Lisa Cohen

Jetstream - Startup Application

Title: Startup allocation request for the storage, exploration, and analysis of the Marine Microbial Eukaryotic Transcriptome Sequencing Project

Abstract: This proposal is requesting resources from the IU/TACC Jetstream cloud system for the purpose of exploring and enhancing open bioinformatics analysis of a large-scale RNAseq data set. The Marine Microbial Eukaryotic Sequencing Project (MMETSP) is a standardized transcriptome data set representing more than 40 phyla. Samples of mRNA were submitted by a large consortium of PIs to the same sequencing facility, yielding approximately 1 TB of sequence data that are now publicly available on NCBI [1]. This is one of the largest public standardized RNAseq datasets available from a diversity of species. We have been working with the MMETSP dataset to develop a de novo transcriptome assembly, annotation, and analysis pipeline that is open and easily accessible for the community of researchers who put the raw data together. Initial pipeline scripts for installing and running open-source bioinformatics software on a subset of these data have been written and tested on Amazon Web Services (AWS) elastic cloud computing (available on github: https://github.com/dib-lab/MMETSP). Allocation of resources on the public Jetstream VM and persistent storage will allow for further exploration of this data set and development of solutions easily accessible by a community of researchers. Elastic cloud computing provides the freedom of installing and frequently updating custom software, building Docker container files to enhance reproducibility, and open data analysis collaboration with tools such as Jupyter notebooks. 

[1] Keeling PJ et al. 2014. The marine microbial eukaryote transcriptome sequencing project (MMETSP): Illuminating the functional diversity of eukaryotic life in the oceans through transcriptome sequencing. PLOS Biology. 12:(6): e1001889.

Resources Applying for:

The following VM resources are requested: Medium, 6 vCPU, 16 GB RAM, 60 GB local storage

With a total of 50,000 SU = 720 assemblies * 6 hrs for Trinity assembly * 6 vCPU + debugging, quality trimming, digital normalization, annotation, reads quantification

In addition, persistent storage is requested:

With a total of 9 TB = 1 TB of raw data x 3 (for assembly intermediate files) x 3 (for annotation, quality trimming, reads quantification files)

Fields of Study:

Biological Sciences

Biological Oceanography
