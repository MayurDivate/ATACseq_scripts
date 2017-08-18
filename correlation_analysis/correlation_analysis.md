# ATAC-seq correlation analysis 

Step 1 : create normalised ATAC-seq signal track
you can use GUAVA tool which automatically creates ATAC-seq track 

Step 2 : calculate correlation using normalised tracks 
Use bwCorr.sh or  bigWigCorrelate UCSC program
  
Step 3 : convert GUAVA BigWig track to  bedGraph format 
Use bw2bdg.sh or 

Step 5 : Generate input for ATACseq_scatteredplot.r
Use unionBDG.sh 

Step 6 : Plot data
Use ATACseq_scatteredplot.r