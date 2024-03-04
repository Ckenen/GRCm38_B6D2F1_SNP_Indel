# GRCm38_C57DBA_SNP_Indel

Generate available variant calls for C57BL/6J and DBA/2J heterozygosis (GRCm38) from MGP variant calls.

## Objective

The Mouse Genomes Project (MGP, https://www.sanger.ac.uk/data/mouse-genomes-project/) uses next generation sequencing technologies to sequence the genomes of key laboratory mouse strains. Here, we integrated the variant calls (SNPs) from C57BL/6NJ and DBA/2J for the analysis of filial generation.

## Workflow

1. Download the datasets from MGP (see `data/00_download.sh`).

2. Next, perform the integration at the `jupyter.ipynb`.