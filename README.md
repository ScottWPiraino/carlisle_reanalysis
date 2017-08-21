# Issues in the statistical detection of data fabrication and data errors in the scientific literature: simulation study and reanalysis of Carlisle, 2017  
  
 This repository contains file to perform a reanalysis of the paper [Data fabrication and other reasons for non-random sampling in 5087 randomised, controlled trials in anaesthetic and general medical journals](http://onlinelibrary.wiley.com/doi/10.1111/anae.13938/full) by Carlisle.  
   
 The file fabrication_analysis.Rmd is an R markdown file which makes a pdf document with text and figures describing the analysis. This file contains all analysis code.  
   
The files plos.csl and carlisle_analysis_library.bib are used my the .Rmd file for formatting and references, but aren't used in the actual analysis.  
  
All data used for the analysis is either genrated by the .Rmd file (for simulations) or is taken from the supplement of the Carlisle paper. Instructions for obtaining this data can be found in the "carlisle_supplemental" folder.  
  
To run the analysis, the core .Rmd file along with the .csl and .bib files should be placed in a folder together, and the data placed in a subfolder of this folder named "carlisle_supplemental" should contain the data files. This can be accomplished by downloading this repository and placing the data files from the Carlisle supplement in the appropriate folder. Then, knitting the .Rmd file should produce the pdf results.
