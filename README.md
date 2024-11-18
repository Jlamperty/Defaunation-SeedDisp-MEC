Code Author: Therese Lamperty, email: jlamperty@gmail.com 

Summary
This repo includes the analysis code, spatial data, and microsatellite data used in Lamperty et al 2024 Molecular Ecology. This study investigates the effects of defaunation caused by overhunting in the Peruvian Amazon on a small-seeded palm species.
The study design uses 3 areas in the Madre de Dios River Basin in Peru that host wildlife (seed disperser) communities affected in varying degrees by defaunation (defaunated, intermediately defaunated, and faunally-intact).

Repo organization
Organizatino is relatively straightforward and code is annotated. 
Data-in folder includes genotype data (alleles called via GeneMapper) ("EUPR_all_genetic_data_20191227.csv"), spatial data ("16Aug2018_LosAmigosVarunsPlot.csv", "16Aug2018_ReservaAmazonicaVarunsPlot.csv", "16Aug2018_TambopataVarunsPlot.csv", "Spatial_sites_master.csv"),
SPAGeDi program outputs (spatial genetic analysis and basic population genetic metrics) ("gen_div_and_per_loc_info.csv", "spagedi-results-intcoh-ref-alleles-weighted.csv" (intcoh = inter cohort), "spagedi-results-withincoh-ref-alleles-weighted.csv" (withincoh = within cohort, or, intra cohort), formatted for ease of analysis and plotting. 

Data-out folder includes results from SPAGeDi program formatted for plotting and analyses, as well as genepop output. 

Code: includes R code to run the analyses.
