![SQANTI3 logo](https://github.com/FJPardoPalacios/public_figures/blob/master/sq3-logo.png)

#		 SQANTI3

SQANTI3 is the newest version of the SQANTI tool ([publication](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5848618/)) that merges features from SQANTI, ([code repository](https://github.com/ConesaLab/SQANTI)) and SQANTI2 ([code repository](https://github.com/Magdoll/SQANTI2)), together with new additions. SQANTI3 will continue as an integrated development aiming to provide the best characterization for your new long read-defined transcriptome. 

SQANTI3 is the first module of the [Functional IsoTranscriptomics (FIT)](https://tapas.org/) framework, that also includes IsoAnnot and tappAS.

## Lastest updates
Current version (06/17/2021): SQANTI3 version 4.0

New features implemented in SQANTI3

**version 4.0:**
* Creation of HTML report. Using the `--report` argument, it is possible to choose which type of report: `html` (default), `pdf`, `both` or `skip`.
* Short-reads processing pipeline included. Now, providing directly your short-read data (FASTA/FASTQ format), SQANTI3 will:
    * Map them against the genome to identify SJ and calculate their coverage.
    * Calculate the "ratio_TSS" value for each isoform of your transcriptome.
    * If pair-end data is provided, isoform expression will be computed using kallisto.
* New subcategories for FSM: Reference match, Alternative 3' UTR, Alternative 5' UTR and Alternative 5' and 3' UTRs.
* IsoAnnotLite implemented to generate tappAS compatible GFF3 files. GFF3 output may incorporate functional annotation labels for model species supported by tappAS.
* New plots:
    *  Saturation curves only plot when `--saturation` option activated.
* Installation provided as a conda yml environment file  

## Wiki

Please, visit our wiki for more detailed information

* [What is SQANTI3?](https://github.com/ConesaLab/SQANTI3/wiki/What-is-SQANTI3%3F)
* [SQANTI3 dependencies and installation](https://github.com/ConesaLab/SQANTI3/wiki/SQANTI3-dependencies-and-installation)
* [Running SQANTI3 Quality Control](https://github.com/ConesaLab/SQANTI3/wiki/Running-SQANTI3-Quality-Control)
* [Running SQANTI3 rules filter](https://github.com/ConesaLab/SQANTI3/wiki/Running-SQANTI3-rules-filter)
* [SQANTI3 output explanation](https://github.com/ConesaLab/SQANTI3/wiki/SQANTI3-output-explanation)

## How to cite SQANTI3

SQANTI3 paper is under construction, but in the meantime it is possible to cite the [original SQANTI paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5848618/).



