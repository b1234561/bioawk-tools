BioAwk
======

Awk based utility scripts for bioinformatics.

Consult the source of each script for documentation (usage, parameters etc).

**Tip**: Adding the source directory as the value of the AWKPATH variable allows you
to run each program file without having to list the full path to it

Some tools may require the GNU Coreutils to be present.
MacOS X users should install homebrew: http://mxcl.github.com/homebrew/ then
use it install the GNU Coreutils::

    brew install coreutils

SAM
---

  * sam2wig.awk - converts the samtools pileup format to wiggle
  
Interval
--------

  * gff2bed.awk - converts GFF to BED format
  * bed2gff.awk - converts BED to GFF
  * chipfrag.awk - chipseq fragment size estimator based on a BED file
  * chopgff.awk - generates a one base long interval at the 5' or 3' of the feature
  * profile.awk - generates a profile from a windowBed output file

Fasta
-----

  * splitfasta.awk - splits a fasta file into smaller files

Fastq
-----

  * randpair.sh - selects random pairs from two fastq files