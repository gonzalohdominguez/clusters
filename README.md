# Gene Distance Calculation
This repository contains two Python scripts, GeneDistance_m1.ipynb and GeneDistance_m2.ipynb, which implement different methods for calculating the distance between genes.

### Method 1: Gene Distance Calculation
This method begins with a thorough search of all genes and their respective locations in the corresponding GFF file. 
For each chromosome/scaffold, the distance between each gene and its neighbors, both in the preceding and following positions, is determined. 
Finally, an average of the distances between all genes in the genome is calculated.

### Method 2: Calculation of the distance between genes
This method starts with an exhaustive search of all genes and their respective locations in the corresponding .gff file. 
For each chromosome/scaffold, the number of genes located 500,000 bp downstream and 500,000 bp upstream of each gene is determined. 
Subsequently, the average number of genes present every 1,000,000 bp in the species is calculated. Lastly, the average distance, in base pairs, between each gene is determined.
