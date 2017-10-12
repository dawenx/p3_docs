# PATRIC September 2017 Data Release

## Data Updates:

### New Genomes and Metadata 

In this release, PATRIC has added >7,500 new genomes and associated metadata, bringing the total number of genomes in PATRIC to over 116,000. The full list of available microbial and host genomes can be accessed here.

This release features 1,668 Klebsiella pneumoniae genomes, which are clinical isolates from Houston Methodist Hospital System and contain AMR panel data. These genomes and related AMR data are exclusively available in PATRIC and were used in constructing new AMR phenotype prediction and Minimum Inhibitory Concentration (MIC) prediction classifiers in PATRIC.

### Annotation and Protein Family Updates

As part of this release, we have updated protein functions and protein families for all public genomes in PATRIC. This is done periodically (usually every four months) to incorporate the latest annotations from the manual curation of underlying subsystems and AMR genes. The genus-specific and cross-genera protein families are also updated to increase the coverage for novel proteins and novel genera added in the database since last update. The new protein annotations and protein families are also deployed in the annotation pipeline. Hence, any new genomes annotated using the PATRIC Annotation Service will receive the latest annotations.

### Specialty Gene Updates

All reference gene databases used for Specialty Gene Annotation have been updated to incorporate the latest data from the original source databases, including CARD, VFDB, Victors, DrugBank and TTD. In addition, we have added two new reference databases: AMR genes from NCBI’s NDARO database and transporter genes from TCDB. The specialty gene annotations for all public genomes in PATRIC have been updated and the new reference databases are deployed as part of the PATRIC Annotation Service.

### Website Updates:

The website updates include minor enhancements and bug fixes identified from recent PATRIC workshops as well as direct user feedback, including the following:

* Streaming of results from the Variation, RNA-seq, and Tn-seq services (i.e. BAM and VCF files) to the Genome Browser directly from the jobs result page.
* Ability to provide SRA Run Accession as input to the Assembly Service, without uploading the read files.
* Improved performance and load times for the Protein Family Sorter and other pages.
* Enhancements to the workspace data management, including efficient copying and moving job results.