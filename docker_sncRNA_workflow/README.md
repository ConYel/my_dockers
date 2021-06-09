## Docker container for the analysis of data from small non-coding RNA-seq

> docker run --rm -ti -v $(pwd):/home/my_data  congelos/sncrna_workflow

### DockerHub: 
> https://hub.docker.com/r/congelos/sncrna_workflow

### It includes:
- bedtools check:[bedtools](https://bedtools.readthedocs.io/en/latest/index.html)
- samtools check:[Samtools](https://www.htslib.org/)
- STAR check:[STAR](https://github.com/alexdobin/STAR)
- cutadapt check:[Cutadapt](https://github.com/marcelm/cutadapt)
- multiqc check:[MultiQC](https://multiqc.info/docs/)
- fastqc check: [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
- trim-galore check: [Trim_Galore](https://github.com/FelixKrueger/TrimGalore/blob/master/Docs/Trim_Galore_User_Guide.md)
- fastq-dl check: [fastq-dl](https://github.com/rpetit3/fastq-dl)
- spar_prepare check: [SPAR](https://bitbucket.org/wanglab-upenn/spar_prepare/src/master/)
- rust's fcat check: [fastest cat in town](https://github.com/mre/fcat)
