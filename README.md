# mckenzie_naturalization

Evaluating fitness variation in hatchery outplants, their first generation wild born offspring and other NORs in the  South Fork McKenzie spring Chinook salmon reintroduction

# Repository Information

This repository contains all information needed to run the analysis associated with the manuscript titled:

A single generation in the wild increases fitness for descendants of hatchery Chinook salmon (_Oncorhynchus tshawytscha_)

For more detail on pedigree inference, the underlying genetic data, and the related, broader evaluation of the McKenzie River spring Chinook salmon reintroduction, see [the appropriate repository](https://github.com/david-dayan/mckenzie_2022). 

# Directory Structure

__(1) Input Data__: Data to run analysis (note that these are very processed data products from the [McKenzie River Evaluation](https://github.com/david-dayan/mckenzie_2022), not the raw data)  
__(2) Analysis__: Computational notebook for final analysis and related files   
__(3) Notes__: Scratch notebooks, meeting minutes, miscellenia  
__(4) Manuscript__: Drafts and revisions of manuscript  



# How to Reproduce Results

If you're looking to reproduce results, run the code on new data, pull some figures, or get into the weeds and play with the code here are some tips to make this easy. 

(1) Open the .rmd file in R studio using R version 3.6.0 (others may work too, but guaranteed to run using 3.6.0). Install the packages (and any dependencies) in the first code chunk.   
(2) Analysis sections are not indepedent. Code chunks rely on object created in the code chunks above. Therefore you must run each chunk IN ORDER. Also, several code chunks have their evaluation flags set to false (e.g. "EVAL = FALSE" in header). Changing these flags may alter the objects in the environmental and lead to non-reproducibility of the analysis. Do not change unless you know what you are doing.
(3)  If you're just looking to run a section and are feeling confident, the finalized environment is available __xxx.Rdata__. You can load this file and use the resulting objects, but keep in mind that some objects change throughout the notebook, so running a code chunk using the final environment may produce different results than originally or throw some errors. Use caution.

