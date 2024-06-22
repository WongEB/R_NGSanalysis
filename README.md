# R_NGSanalysis

##Convert genotype file from "A/A" to "1/1" based on the reference and alternate allele
###Bash
##Ref: https://www.biostars.org/p/9549575/ | https://www.thegeekstuff.com/2010/02/awk-conditional-statements/
##awk '{if ($3 <10)print $1,$2,$3="c"; else print $1,$2,$3="s"}'
awk '{if ($2=)}'
