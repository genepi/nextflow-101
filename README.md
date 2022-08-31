# nextflow-101
A simple Nextflow pipeline to demonstrate basic features

```
git clone https://github.com/genepi/nextflow-101
cd nextflow-101
docker build -t genepi/nf-101 . # don't ignore the dot
nextflow run main.nf -profile test,docker
```
