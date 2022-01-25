# Galaxy-Workflows
NGS Data Analysis workflow pipelines for Variant Calling and RNS-Seq analysis using the following tools -

Uploaded FastQ files 

Quality Control   
	FastQC
	FastQC Groomer
		
Sequence Analysis
	Mapping with BWA-MEM
  ISAT - sequence alignment

Variant Calling
	FreeBayes
	VCFfilter - filter for quality
	VCFselectsamples - select necessary records from the VSCF file	
	ANNOVAR - Annotate the variants
	Concatenate Datasets
	Group data
	Sort data
  
featureCounts - Measure gene expression

htseq-count - count the number of reads mapping to each feature
