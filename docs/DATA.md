# Example data

Example data generated for different types of amplicons using Oxford Nanopore and PacBio.

#### Oxford Nanopore

Target | Sample | Sequencing setup | UMI consensus | Raw yield (Gbp) | Raw reads (M) | UMI reads (K)| Mean Length (bp) | Raw data fastq | Raw data fast5 | UMI data fasta | Reference
---|---|---|---|---|---|---|---|---|---|---|---
Bacterial rRNA operon (~4300 bp) | ZymoBIOMICS Microbial Community DNA Standard (D6306, lot no. ZRC190811) | MinION, R10, guppy3.4.4-hac | racon(v1.4.3)x2, medaka(v0.11.2)x2 | 18.9 | 4.4 | 23.4 | 4381 | [ERR3813594](https://www.ebi.ac.uk/ena/data/view/ERR3813594) | [ERR3813597](https://www.ebi.ac.uk/ena/data/view/ERR3813597) | [ERZ1284843](https://www.ebi.ac.uk/ena/data/view/ERZ1284843) | [Karst *et al*, 2020](https://www.biorxiv.org/content/10.1101/645903v3)
Bacterial metagenome (~4500 bp) | ZymoBIOMICS Microbial Community DNA Standard (D6306, lot no. ZRC190811) | MinION, R10, guppy3.2.4-hac | racon(v1.4.3)x1, medaka(v0.8.1)x1 | 10.4 | 2.7 | 3.7 | 4476 | [ERR3813593](https://www.ebi.ac.uk/ena/data/view/ERR3813593) | [ERR3813596](https://www.ebi.ac.uk/ena/data/view/ERR3813596) | [ERZ1284839](https://www.ebi.ac.uk/ena/data/view/ERZ1284839) | [Karst *et al*, 2020](https://www.biorxiv.org/content/10.1101/645903v3)


#### PacBio

Target | Sample | Sequencing setup | UMI consensus | Raw yield (Gbp) | Raw reads (M) | CCS reads (M) | UMI reads (K) | Mean Length (bp) | Subreads data (bam) | CCS data (bam) | UMI data fasta | Reference
---|---|---|---|---|---|---|---|---|---|---|---|---
Bacterial rRNA operon (~4300 bp) | ZymoBIOMICS Microbial Community DNA Standard (D6306, lot no. ZRC190811) | Sequel II, SMRT cell 8M, Sequencing Kit 1.0, CCS (v3.4.1) | racon(v1.4.3)x2 | 161.4 | 36.6 | 1.9 | 39.7 | 4376 | [ERR3813247](https://www.ebi.ac.uk/ena/data/view/ERR3813247) | [ERR3813246](https://www.ebi.ac.uk/ena/data/view/ERR3813246) | [ERZ1284840](https://www.ebi.ac.uk/ena/data/view/ERZ1284840) | [Karst *et al*, 2020](https://www.biorxiv.org/content/10.1101/645903v3)
