# Snail Coiling Dia2 Analysis

A small bioinformatics project comparing the dextral and sinistral Dia2 alleles of *Lymnaea stagnalis*.

## About the Project

This project looks at the Dia2 gene in *Lymnaea stagnalis* and compares the dextral and sinistral alleles at the sequence and protein levels.

The main focus is the sequence change found in the sinistral allele and its effect on the resulting Dia2 protein.

## Sequences Used

The analysis used the following NCBI GenBank sequences:

| Type | Accession | Description |
|---|---|---|
| Dextral allele | KU341304.1 | Full-length dia2 mRNA |
| Sinistral allele | KU341305.1 | Truncated dia2 mRNA |
| Dextral protein | ALX18036.1 | Full-length Dia2 protein |
| Sinistral protein | ALX18037.1 | Truncated Dia2 protein |

## Analysis

The main steps of the project were:

1. Retrieved the Dia2 nucleotide sequences from NCBI GenBank.
2. Compared the sequences using BLAST.
3. Examined the annotated CDS and mutation information.
4. Compared the predicted protein products of the two alleles.
5. Examined the annotated protein domains of the dextral Dia2 protein.
6. Visualized the difference between the full-length and truncated proteins.
7. Summarized the possible effect of the frameshift mutation on the Dia2 protein.

## Main Finding

The dextral allele contains a complete CDS that produces a 1040-aa Dia2 protein.

The sinistral allele contains a one-base-pair deletion reported at position 243-244. The deleted base is cytosine (C).

This deletion causes a frameshift and results in a highly truncated 42-aa Dia2 protein.

The dextral Dia2 protein contains three major annotated regions:

- GBD: 3–175 aa
- FH3: 179–370 aa
- FH2: 523–889 aa

These major annotated regions are absent from the 42-aa truncated sinistral protein.

## Figures

### Dia2 Protein Domain Architecture

The figure compares the domain architecture of the dextral and sinistral Dia2 proteins.

![Dia2 protein domain architecture](figures/domain_architecture_dia2.png)

### Frameshift Mutation

This figure summarizes the relationship between the one-base-pair deletion in the sinistral allele, the resulting frameshift, and the truncated Dia2 protein.

![Frameshift mutation in dia2](figures/dia2_frameshift_mutation.png)

## Data

The `data` folder contains the nucleotide and protein sequence files used in the analysis, together with sequence metadata.

## Project Notes

This is a small learning-based bioinformatics project. The analysis is based on publicly available sequence information and annotated protein features from NCBI GenBank.

The results suggest a strong difference between the dextral and sinistral Dia2 proteins. However, this sequence-based analysis alone cannot establish the exact cellular mechanism responsible for shell coiling.

## Data Source

NCBI GenBank

Accession numbers:

- KU341304.1
- KU341305.1
- ALX18036.1
- ALX18037.1
