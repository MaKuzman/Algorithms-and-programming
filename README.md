# Algorithms-and-programming
title: "R workshop"
author: "Maja Kuzman"
output:
  html_document: default


#The basics (if needed)  

####Introduction  
- R
- R markdown, R notebook

#####Vectors:  

- subsetting, recycling  
- Vector types: numeric, logical, character, complex  
- Some operations : +,-, /, *, %/%, %%, ==, !=  
- Some functions: any, all, example, help, ?, ??, sum, sd, mean, factorial, abs  

#####Matrices:  
- subsetting, basic operations  

#####Functions:  
- Basic function format, environments, return, recursions  

#####Flow control in R:  
- if, if-else, ifelse, for, while, break, next  

#####Lists  
- basic operations; accessing elements, list structure 
- lapply, sapply, tapply, by, do.call
- ... as parameter

#####Factors
- structure, addition of elements, addition of new levels
- conversion to numeric  

--- 

#Data manipulation  

####Data frames  
- read in: read.table, read.csv, read.tsv
- basics - subset() and []
- merge, order, unique

####Package: dplyr  
- filter, slice, select
- %>%, grouping
- summarise, arrange, lead, lag, n, count
- mutate, mutate_all, transmute

####Package: data.table  
- i: selecting rows
- j: selecting columns, returning list list() / .()
- by: by
      
####Regular expressions  
- grep
- Special characters: ^$ \\ . + * ?
- Special brackets: [], (), {}. \\\\1
- stringr package

####Package: tidyr   
#####What is clean data?    
- rows = observations   
- columns = attributes  

#####How to clean up messy data:  
- spread: Each column single attribute    
- gather: Column headers are variable names    
- sepatrate: Busy columns  
- merge multiple tables (baseR, dplyr, data.table)  
  
---  
      
#Data visualization  
- Plots in base R VS ggplot examples  

####Some useful graphs:
- Scatter plot  
- Q-Q plot  
- Histograms  
- Density plots  
- correlation matrix (package:corrplot)  
- Heatmap (package: pheatmap)  

####Package: ggplot2
- Basics: ggplot(dataframe, aes(x,y)) 
- different layer examples: geom_point(), geom_histogram(), geom_smooth(), geom_bar(), geom_boxplot(), geom_density(), ...  
- groupings: group, fill, facets    
- Other: titles, axes, legends, colors, themes   

####Interactive graphs     
- Interactive graphs examples with ggplotly  
- shiny  

#Advanced topics: Bioconductor  
####Package:Biostrings:  
- BSgenome  
- get sequence by GRanges - getSeq   
- useful functions: complement, reverseComplement, reverse,c  
- subseq, Views  
- alphabetFrequency, mono, di, trinucleotideFrequency, oligonucleotideFrequency  
- translate, consensusMatrix, matchPattern, PairwiseAlignment  

####Package:shortRead  
- Handling FastQ reads  
- Handling alignments  

####Package: biomaRt  
- choosing mart (version, type, organism) useEnsembl  
- choosing dataset - listDatasets, useDataset, listAttributes  
- getting the dataset - getBM  

####Package: GenomicRanges and IRanges:  
- defining IRanges and accessing elements  
- some functions: reduce, disjoin, findOverlaps, countOverlaps, coverage  
- defining GRanges and applying functions on them  
