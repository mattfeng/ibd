# The Human Microbiome Project (HMP)

## A quick introduction to the HMP
The HMP was split into two phases: **HMP-1**, and **iHMP (Integrative Human Microbiome Project)**.

> HMP-1 characterized the microbial communities found at several different sites on the human body: nasal passages, oral cavity, skin, gastrointestinal tract, and urogenital tract, and examined the role of these microbes in human health and disease.

_Read [a detailed overview of HMP-1](https://hmpdacc.org/hmp/overview/)._

The iHMP has _three study cohorts_, each examining a different microbiome-associated condition: (1) pregnancy and preterm birth, (2) onset of inflammatory bowel disease, and (3) onset of type 2 diabetes. The studies are named MOMS-PI, IBDMDB, and iPOP, respectively.

Data collection from the three cohorts has concluded.
- MOMS-PI finished collecting data in 2019.
- IBD finished collecting data in 2020.
- iPOP finished collecting data in 2016.

_Read [this overview](https://hmpdacc.org/ihmp/overview/) for more details on the three different cohorts of the iHMP._

### Further reading
- [The Pregnancy and Preterm Birth study website](http://vmc.vcu.edu/momspi).
- [The IBD study website](https://www.ibdmdb.org/).
- [The Type 2 Diabetes study website](https://med.stanford.edu/ipop.html).

## The data
The size of all the data collected from both phases of the HMP is **48.54 TB**. Luckily, for many of our analyses, we will only require a fraction of that.

### Downloading the data
Because of the large sizes of the data, tools have been created for downloading the data.
- https://github.com/IGS/portal_client

### Analyzing HMP-1 Data
The total size of HMP-1 data is about **38 TB**.

#### Data formats
There are a few different file formats for the sample data:

##### Standard Flowgram Format (SFF) (`.sff`)
Standard flowgram format (SFF) is a binary file format used to encode results of pyrosequencing from the 454 Life Sciences platform for high-throughput sequencing. Because 454 Life Sciences was shutdown in 2013, SFF is no longer a common format.

The SFF format can be converted to FASTQ format using [BioPython](https://biopython.org/docs/1.75/api/Bio.SeqIO.SffIO.html).

##### FASTA (`.fsa`, `.fasta`)

### Analyzing iHMP Data

#### Data formats

##### Biological Observation Matrix (`.biom`)
