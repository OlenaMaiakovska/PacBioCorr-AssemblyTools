# PacBioCorr-AssemblyTools
Here is the list of tools with the pipeline for read correction and hybrid assembly. 

Third-technology sequencing brought by Pacbioscience or Oxford Nanopore is able to produce
average long read length of more than 10,000 bp and thus can advantageously be used to improve
the genome assembly. In fact, long reads span more repetitive elements and thus can produce
more contiguous reconstruction of the genome. However, long reads have raw error rate ranging
from 10% to 15%, requiring a preliminary stage of correction before the assembly process.

The available correction software are mainly based on two strategies :
	
	hybrid correction (both long reads and short reads are required) ;
	denovo correction (only long reads are required) ;
Hybrid correction uses short reads, such as Illumina, which have a much lower error rate, to
correct long reads. The second strategy consists in aligning long reads against themselves.
