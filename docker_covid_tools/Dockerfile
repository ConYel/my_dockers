FROM continuumio/miniconda3:4.10.3-alpine

RUN conda create -n tools -qy -c bioconda git fastqc bwa pip megahit samtools \
freebayes=1.3.2 snippy pigz qualimap && \
conda create -n R_bio -qy -c bioconda bioconductor-biostrings && \
conda create -n bcftools -qy -c bioconda bcftools && \
pip3 install cutadapt multiqc

COPY add_file_name_to_fasta_header.R /home/

RUN chmod 700 /home/add_file_name_to_fasta_header.R

WORKDIR /home

CMD ["/bin/bash"]
