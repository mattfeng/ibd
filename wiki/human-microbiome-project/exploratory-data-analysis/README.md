# Exploring the HMP Data

## Links
- [HMP Project Catalog](https://www.hmpdacc.org/hmp/catalog/)
- [HMP1 Data Model](https://www.hmpdacc.org/overview/data-model.php)
- [HMP1 Reference Genomes](https://www.hmpdacc.org/hmp/reference_genomes/reference_genomes.php)
  - HMP1 sequenced over 2000 reference genomes of different microbes to help with downstream identification (when sequencing data from host microbiomes).
- [USDA Metagenomics Tutorial (Assembly Approach)](https://usda-ars-gbru.github.io/Microbiome-workshop/tutorials/metagenomics/)

## TODO
- Learn
  1. [Biom file format](http://biom-format.org/documentation/biom_format.html)
  2. [Genome Assembly](https://www.youtube.com/watch?v=ZYW2AeDE6wU)
- Tutorial
  - Describe the BIOM file format
  - [Studies and abbrevations](https://portal.hmpdacc.org/projects/t)
  - Representative example for each data type

## Basics
- [BIOM file format](http://biom-format.org/documentation/biom_format.html)

## Data model
- [Paper (Cell Host and Microbe)](https://www.cell.com/cell-host-microbe/fulltext/S1931-3128(14)00306-0)
- [Data types](https://www.cell.com/action/showFullTableHTML?isHtml=true&tableId=tbl2&pii=S1931-3128%2814%2900306-0)
  - 16S rRNA gene survey
    - `16s_raw_seq_set`
    - `16s_trimmed_seq_set`
  - Whole metagenome shotgun sequences
    - `wgs_raw_seq_set`
    - `wgs_assembled_seq_set`
  - Whole metatranscriptome shotgun sequences
    - `microb_transcriptomics_raw_seq_set`
  - Whole virome shotgun sequences
    - `viral_seq_set`
  - Bacterial isolates
  - Single-cell genome sequences
  - Single-cell RNA sequences
  - LC-MS/MS peptide profiles
  - Human subject whole genome sequences
    - `host_wgs_raw_seq_set`
  - (Human subject) Whole exome sequences
    - ?
  - (Human subject) Whole transcriptome sequences
    - `host_transcriptomics_raw_seq_set`
  - Cytokines
    - `cytokine`
  - DNA methylation profiles
    - `host_epigenetics_raw_seq_set` (?)
  - Fecal calprotectin proteins
    - ?
  - Serology
    - `serology`
  - Human subject contaminating genome sequences
    - ?
  - Interactomes
    - ?
  - Intestinal epithelial cell profiles
    - ?
  - Metabolomes
    - `metabolome`
  - Lipidomes
    - `lipidome`

- Data type
  - `abundance_matrix`
  - `proteome_nonpride`
  - `clustered_seq_set`
  - `host_variant_call`
  - `annotation`
  - `alignment`

## Abbreviations
- Sources
  1. [HMP1 Version 1](https://www.hmpdacc.org/hmp/resources/data_browser.php)
  2. [HMP1 Version 2](https://www.hmpdacc.org/hmp/resources/data_browser.php)
  3. [HMP Studies](https://portal.hmpdacc.org/projects/t)
  4. [What does AGP stand for?](https://www.biostars.org/p/43377/)
  4. [Microbiome Analyses](https://www.hmpdacc.org/hmp/micro_analysis/microbiome_analyses.php)
- **HHS**. healthy human subject (3)
- **hmcgi**. co-assembly annotated gene index. (2)
- **hmgi**.
- **hmasm**.
- **hmrarg**. read alignments to reference gnomes
- **hmbsa**. body-site specific assemblies
- File formats
  - **AGP (A Golden Path)**. a description of the assembly of an object, e.g. a chromosome, by listing all its components (clones) in order whilst specifying exact coordinates
- **WUGI**. Washington University Genome Institute
- **mWGS**. whole metagenome shotgun sequencing (4)

## Questions
- What is a whole metagenome assembly? Isn't it a community of genomes?