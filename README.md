# rprofile
repeatWrench is disigned to profile repetitive elements of the human genome from RNA-Seq data

How to run for multiple samples : 

while read line; do echo "~/anaconda/bin/python ~/code2/rprofile/rprofile.py <dirBams>/${line}.bam  $PWD/${line}">run_${line}.sh;done<sample.txt

