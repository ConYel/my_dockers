FROM continuumio/miniconda3:4.10.3-alpine

RUN conda create -n tools -qy -c bioconda git fastqc bwa pip megahit samtools \
freebayes=1.3.2 snippy pigz && \
conda create -n R_bio -qy -c bioconda bioconductor-biostrings && \
conda create -n bcftools -qy -c bioconda bcftools && \
conda activate tools && \
pip3 install cutadapt multiqc
