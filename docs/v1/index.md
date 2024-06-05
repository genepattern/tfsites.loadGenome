# tfsites.LoadGenome v1

**Author(s):** Joe Solvason  

**Contact:** Joe Solvason (solvason@eng.ucsd.edu)

**Adapted as a GenePattern Module by:** Ted Liefeld (jliefeld@cloud.ucsd.edu)

**Task Type:** Transciption factor analysis

**LSID:**  urn:lsid:genepattern.org:module.analysis:00443


## Introduction

`LoadGenome` converts a genome file given by the user into binary form (i.e. a pickled file). This pickled file can be used for other methods in `tfsites` that involve genome analysis. 


## Methodology

The Python tool `SeqIO` is used to convert the genome (in .fasta format) into a Pythonic dictionary. In the dictionary, each chromosome is mapped to its DNA sequence. This dictionary can then be stored as a pickled file. 


## Parameters

<span style="color: red;">*</span> indicates required parameter

### Inputs and Outputs

- <span style="color: red;">*</span>**original genome (.fasta)**
    - This file contains the genome that the user would like to analyze.
- <span style="color: red;">*</span>**pickled genome output filename (.pkl)**
    - This file contains the binary form of a Pythonic dictionary that maps each chromosome in the genome to its DNA sequence. 


## Input Files

1.  Genome Input (.fasta)

```
>chr1
CCTGGTGCTCCCACAAAGGAGAAGGGCTGATCACTCAAAGTTGCGAACACCAAGCTCAACAATGAGCCCTGGAAAATTTCAG...
>chr2
GGGGAAGCAAGGCGGAGTTGGGCAGCTCGTGTTCAATGGGTAGAGTTTCAGGCTGGGGTGATGGAAGGGTGCTGGAAATGAG...
```
       
## Output Files

1.  Pickled Genome Output (.pkl)

```
a binary file cannot be previewed but it is stored as a pythonic dictionary in the following format:

{'chr1':'CCTGGTGCTCCCACAAAGGAGAAGGGCTGATCACTCAAAGTTGCGAACACCAAGCTCAACAATGAGCCCTGGAAAATTTCAG', ...} 
```

    
## Example Data

Example input data is available at [https://datasets.genepattern.org/data/module_support_files/tfsites/hg38.fa ](https://datasets.genepattern.org/data/module_support_files/tfsites/hg38.fa)

    
## Version Comments

- **1.0.2** (2024-05-10): Parameter names updated.
- **1.0.1** (2024-02-02): Draft completed.
- **1.0.0** (2023-01-12): Initial draft of document scaffold.
