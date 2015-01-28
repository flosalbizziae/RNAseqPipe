# RNAseqPipe
RNA-seq analysis pipeline
####
This is a pipeline for RNAseq analysis based on Tophat and Cufflinks.
####
Author: Xue Lin, Jian Li
Date: 28th Jan 2015
Contact: flosalbizziae@gmail.com/baoyunya@qq.com
	jianlij@gmail.com/jian_lij@163.com
###
Steps of the pipeline: 
1 quality control
2 trim adapter and low quality bases
3 quality control
4 alignment the reads to the genome
5 assemble expressed genes and transcripts
6 identify differentially expressed genes and transcripts
7 visualization
###
Installation:
The package is written in shell and perl, regretfully it only support Linux OS.
After downloading the package, uncompress the package:

tar -zxcf RNAseqPipe.tar.gz

Enviroment requirements:
Before using of the pipeline, you should have the following applications installed on your OS:
python
perl
R
fastqc
cutadapt
samstat
bowtie
tophat
cufflinks


Usage
Then you cd into the folder, type:

rnaseqpipe -h

to get help documents.

Release note:
The RANseqPipe v 0.1 is the first release of the pipeline, and this pipeline is built for the short reads systems like illumina.
The pipeline is valid both for single end and paried end suquenicng data.

