# tfsites.LoadGenome v1

**Author(s):** Joe Solvason  

**Contact:** Joe Solvason (solvason@eng.ucsd.edu)

**Adapted as a GenePattern Module by:** Ted Liefeld (jliefeld@cloud.ucsd.edu)

**Task Type:** Transciption factor analysis

**LSID:**  urn:lsid:genepattern.org:module.analysis:00443


## Introduction

tfsites.LoadGenome converts fasta file into dictionary and stores it as a pickled file to be used in subsequet tfsites modules.

## Functionality

TBD

## Methodology

TBD

## Parameters

<span style="color: red;">*</span> indicates required parameter

- **genome**<span style="color: red;">*</span>
    - Genome to be analyzed in fasta format.
- **out filename**<span style="color: red;">*</span>
    - Out file name for the pickled genome.


## Input Files

1.  genome.  fasta formatted genome file. 
    


## Creating Input Files from User Data

TBD Describe how to get common data formats into the format needed here
       
## Output Files

  1.pickle: <output filename> pickle formatted dictionary.
    
  
## Example Data

Example input data is available at [https://datasets.genepattern.org/data/module_support_files/tfsites/hg38.fa ](https://datasets.genepattern.org/data/module_support_files/tfsites/hg38.fa)
    
## References

Cancer Genome Atlas Network. Comprehensive genomic characterization of head and neck squamous cell carcinomas. Nature. 2015 Jan 29;517(7536):576-82. doi: 10.1038/nature14129. PMID: 25631445; PMCID: PMC4311405.
    
## Version Comments

- **1.0.0** (2023-01-12): Initial draft of document scaffold.
