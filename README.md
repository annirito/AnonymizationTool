# AnonymizationTool
The anonymization app deletes personal data from .fcs/.lmd files. In the process, the entered file is overwritten in the affected areas or field contents are deleted. This enables the further use of the anonymized file for physicians and doctors. 

## Installation

Install the package by using Github:
> remotes::install_github("PLAIT-project/AnonymizationTool")

Or just run the AnonymizationTool in R with following Command:
> shiny::runGitHub("AnonymizationTool", "PLAIT-project", subdir = "R")

Install the required packages:\
see here: http://137.248.121.81:9798/plait/anonymisierungsapp/ (link is only accessible from the university network of the University of Marburg.)
> requiredPackages <- c("shiny", "shinyjs", "shinyFiles", "shinyFeedback", "Rcpp") new.packages <- requiredPackages[!(requiredPackages %in% installed.packages()[,"Package"])]  
> if(length(new.packages)) install.packages(new.packages, quiet=TRUE)\
> invisible(lapply(requiredPackages, library, character.only = TRUE)) 

More detailed instructions can be found in the Manual. 

## Manual
The full manual for physicians, doctors and scientists who have .fcs/.lmds files for anonymization, is available here: http://137.248.121.81:9798/plait/anonymisierungsapp/ (link is only accessible from the university network of the University of Marburg.)
