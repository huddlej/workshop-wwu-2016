---
layout: default
---

## Viewing variants in the UCSC Genome Browser

  * Go to the [UCSC Genome Browser](http://genome.ucsc.edu/).
  * Select the "Feb. 2009" human assembly (i.e., "hg19").
  * Click "Add custom tracks" button.
  * Paste the following code into the first text area:

    track name="1000 Genomes SVs" type=vcfTabix bigDataUrl=ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/phase3/integrated_sv_map/ALL.wgs.integrated_sv_map_v2.20130502.svs.genotypes.vcf.gz

  * Click "Submit".
  * Click the "Genome Browser" link at the top of the page.
  * Search for "HERC2", select the autocompleted text provided, and click "go".
