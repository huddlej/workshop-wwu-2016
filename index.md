---
layout: default
---

## Resources for the workshop

  * [Slides](slides/index.html)
  * File format specifications
    * [High-throughput sequencing (HTS) specifications](http://samtools.github.io/hts-specs/)
    * [Common genomic annotation formats](http://genome.ucsc.edu/FAQ/FAQformat.html)
  * [Glossary](glossary.html)

### Part 1: Sequence review

  * [FASTQ format](http://maq.sourceforge.net/fastq.shtml)
  * [FASTA format](http://genetics.bwh.harvard.edu/pph/FASTA.html)
  * [FASTQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/) - Quality control for FASTQ data

### Part 2: Sequence alignment

  * [SAM specification](http://samtools.github.io/hts-specs/SAMv1.pdf)
  * [BWA (Burrows-Wheeler Aligner)](http://bio-bwa.sourceforge.net/) - standard short read aligner
  * [samtools](http://www.htslib.org/) - SAM/BAM analysis toolkit

### Part 3: Variant calling

  * [VCF specification](http://samtools.github.io/hts-specs/VCFv4.3.pdf)
  * [freebayes](https://github.com/ekg/freebayes) - Bayesian SNV and small indel caller
  * [vcflib](https://github.com/vcflib/vcflib) - VCF analysis toolkit from the author of freebayes
  * [bcftools](https://samtools.github.io/bcftools/) - VCF analysis toolkit from the authors of samtools
  * [Viewing variants in UCSC Genome Browser](ucsc_browser.html)

## Continuing education

### Command line tools

  * [bash shell](http://tiswww.case.edu/php/chet/bash/bashref.html) - common command line interface and scripting environment
  * [awk](https://www.gnu.org/software/gawk/manual/html_node/index.html) - powerful command line programming language for editing and filtering text files
  * [sed](https://www.gnu.org/software/sed/manual/sed.html) - stream text editor for simple text transformation and filtering

### Tools for bioinformatics pipelines

  * [git](https://git-scm.com/) - version control for software, analysis pipelines, and documentation
  * [bedtools](http://bedtools.readthedocs.org/en/latest/) - industry-standard toolkit for manipulation of genomic intervals
  * [Snakemake](https://bitbucket.org/snakemake/snakemake/wiki/Home) - bioinformatics workflow management in a Pythonic domain-specific language (DSL)
  * [Ruffus](http://www.ruffus.org.uk/) - bioinformatics workflow management in pure Python
  * [GNU make](https://www.gnu.org/software/make/manual/make.html) - venerable dependency management tool suited to simple

### Sequence alignment

  * [mrsFAST](http://sfu-compbio.github.io/mrsfast/) - short-read aligner optimized for finding all possible mappings for each given read
  * [BLASR](https://github.com/PacificBiosciences/blasr) - Long-read aligner originally designed for PacBio data
  * [STAR](https://github.com/alexdobin/STAR) - RNA-seq aligner
  * [TopHat](https://ccb.jhu.edu/software/tophat/index.shtml) - RNA-seq aligner

### Variant calling

  * [samtools](http://www.htslib.org/workflow/#mapping_to_variant) - Calling SNVs and small indels
  * [GATK](https://www.broadinstitute.org/gatk/) - SNV and small indel caller and analysis toolkit
  * [WHAM](http://zeeev.github.io/wham/) - structural variant (SV) caller and genotyper using soft clipped read pairs
  * [Delly](https://github.com/tobiasrausch/delly) - SV caller using read pairs and split reads
  * [LUMPY](https://github.com/arq5x/lumpy-sv) - SV caller using read pairs and split reads
  * [VariationHunter](http://variationhunter.sourceforge.net/Home) - SV caller using read pairs
  * [SnpSift](http://snpeff.sourceforge.net/SnpSift.html) - VCF analysis toolkit
  * [SnpEff](http://snpeff.sourceforge.net/) - Variant annotator and effect predictor for SNVs and small indels
  * [SeattleSeq](http://snp.gs.washington.edu/SeattleSeqAnnotation138/) - Variant annotator

### De novo assembly

  * [Canu](http://canu.readthedocs.org/en/stable/) - long, noisy read assembler using [Overlap-Layout-Consensus method](http://gcat.davidson.edu/phast/olc.html)
  * [FALCON](https://github.com/PacificBiosciences/FALCON) - long, noisy read assembler using [string graph method](http://bioinformatics.oxfordjournals.org/content/21/suppl_2/ii79.full.pdf)
  * [minimus2](http://amos.sourceforge.net/wiki/index.php/Minimus2) - simple assembly of small genomes or sequences
  * [SOAPdenovo](http://soap.genomics.org.cn/soapdenovo.html) - short read assembler
  * [AbySS](https://github.com/bcgsc/abyss) - short read assembler
  * [Assemblathon](http://assemblathon.org/) - practical comparison of major de novo assemblers

### Genomic visualization

  * [UCSC Genome Browser](http://genome.ucsc.edu/)
  * [Integrative Genomics Viewer (IGV)](https://www.broadinstitute.org/igv/)
  * [PyBamView](http://melissagymrek.com/pybamview/)

### Sequence annotation

  * [RepeatMasker](http://www.repeatmasker.org/)
  * [Tandem Repeats Finder (TRF)](https://tandem.bu.edu/trf/trf.html)
  * [MAKER](http://www.yandell-lab.org/software/maker.html) - gene annotation

### Public sequence databases and services

  * [National Center for Biotechnology Information (NCBI)](http://www.ncbi.nlm.nih.gov/)
  * [European Bioinformatics Institute (EBI)](http://www.ebi.ac.uk/)
  * [DNA Data Bank of Japan (DDBJ)](http://www.ddbj.nig.ac.jp/)
