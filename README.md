# Multi-sector 4Ws review

This repository contains the cleaning script for producing the consolidated 4Ws dataset as well as the script for associated reports and presentations. 

The most important file in this repository is `cleaning_script.Rmd`. This an Rmarkdown file containing the code necessary to first, read in and clean 4Ws from each cluster and second, consolidate them into one file. 

For future reference, a public version of the cleaning script for the Cash Working Group 4Ws has been included (`cwg_clean_export.Rmd`). The actual script cannot be shared -- that is in a private repository as it contains partner names and partner codes. 

Only the presentation, `cva_4ws_presentation.Rmd`, is updated to May 19 2023. This was the same presentation used in the ICCG meeting on May 24 2023. The interactive maps for the community-level maps in that presentation may be found in this [repository](https://github.com/northwest-syria-cash-working-group/multisector_4ws_maps); it was published separately to prevent the presentation from loading too slowly. 

Of interest as well is the `cluster_calculations.Rmd`. This is where the formulas for calculating cumulative and monthly beneficiaries reached for each of the clusters are collected. Only Education's and Nutrition's calculations are not replicable.

The report, `multisector_4ws_review.Rmd` has not been updated. Portions of the text have also not been cleared for public sharing. However, it does contain many elements not present in the presentation, such the correlations between clusters as well as correlations between activities. There are a number of interactive tables within the report as well. However, even though the code may knit, the data has not been updated to reflect the latest round of 4Ws data. 

A point for the future: we should also perform this analysis on 2022 data (though the code will need to be adjusted, given that the templates have changed slightly). This will be important in identifying if we have been historically biased towards certain areas or if this is a new phenomenon. 
 
