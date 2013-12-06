## The script generated bedGraphs with log fold changes of IP vs. input DNA as its score
## Use for RNAPol2 ChIPseq data to generate binding profiles
##
## usage python bam_to_window_bedGraph.py 
## input : bam files of both IP and control
## output : GFF file of given window size, output file from multiBamCov, bedGraphs of IP normalized by control. Gives log2(fold changes) as its score. 
## requires : multiBamCov and samtools
## multiBamCov http://bedtools.readthedocs.org/en/latest/content/tools/multicov.html
## samtools http://samtools.sourceforge.net/
##
## currently only runs for maize and arabidopsis (as genome size need to be predefined)
##
## written by Jawon Song
## questions to jawon 'at' tacc 'dot' utexas.edu
##
## Updates 12/06/2013 : Initial update
