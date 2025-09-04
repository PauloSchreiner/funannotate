# DESCRIPTION

Intended for genome-only annotations. Written based on the genome-only funannotate tutorial available at https://funannotate.readthedocs.io/en/latest/tutorials.html#genome-assembly-only


# NEXT STEPS

1. Add the rest of the rules
2. Add rules to analyze results 


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
