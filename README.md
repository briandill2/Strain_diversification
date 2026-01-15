This R markdown file written in the R programming language can be used to reproduce all results in the manuscript "Isolation by distance promotes strain diversification in the wild mouse gut microbiota". 

The code has been tested in R v4.5.0. The install time of required libraries is typically less than 1 hour on a standard desktop computer. 

To run the analysis:
1) unzip `strain_diversification_inputs.tar.gz` in the working directory with `tar -xzvf strain_diversification_input.tar.gz`.
2) Open `MAG_instrain_analysis.Rmd` in RStudio (or another interactive IDE).
3) Run all code chunks in order. 

Expected outputs are described in the R script. The expected runtime for all analyses on a standard desktop computer is < 4 hours. 

The following R libraries are required:  
geosphere  
ape  
vegan  
MKinfer  
ecodist  
phytools  
tidyverse  
nlme  
permuco  
DescTools
