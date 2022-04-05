# COVIDseq_to_peptide
A tiny script to convert COVID consensus genome to peptide sequence.

SARS-CoV-2 Reference was taken from [NCBI](https://www.ncbi.nlm.nih.gov/sars-cov-2/)




## Based on these tools
|Tools|Version/Links|
|---|---|
|`gffread`|cufflinks-2.2.1 |
|`faTrans`|https://hgdownload.soe.ucsc.edu/admin/exe/linux.x86_64/faTrans |




## Usage

    ./convert.sh {sample.fasta}
    

## Output
|File name|Description|
|---|---|
|orf/{sample}.fasta|Parsed sequences based on SARS-CoV-2 gff3|
|peptide/{sample}.fasta|Amino acid sequences translated from orf/{sample}.fasta |
