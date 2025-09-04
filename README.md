to-do:
add envs properly into envs
add all to github



# QUICKSTART

## 1. Download Databases 

``` bash
export FUNANNOTATE_DB=/home/paulo/funannotate_db 
mkdir -p $FUNANNOTATE_DB
funannotate setup -i all --database $FUNANNOTATE_DB
```

Responder: 
- Qual a importância disso?
- Em que casos não usar -i all?



## Configure config.yaml

samples:
  NCYC357:
    location: "data/genomes/NCYC357_genome.fa"
    species: "Saccharomyces sp."
    strain: "NCYC357"
    busco: "saccharomycetes"
