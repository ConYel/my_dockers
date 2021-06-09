## Docker container for the analysis of data from small non-coding RNA-sec

> docker run --rm -v $(pwd):/home/0 -p 8787:8787 -e PASSWORD=12345 -e USER=$UID congelos/sncRNA_workflow

### DockerHub: 
> https://hub.docker.com/r/congelos/rocker_tidyverse_plus_de_pckages

### It includes:
- bedtools 
- samtools 
- STAR 
- cutadapt 
- multiqc 
- fastqc 
- trim-galore 
- fastq-dl check: [fastq-dl](https://github.com/rpetit3/fastq-dl)
- spar_prepare check: [SPAR](https://bitbucket.org/wanglab-upenn/spar_prepare/src/master/)
- rust's fcat check: [fastest cat in town](https://github.com/mre/fcat)
