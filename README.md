

PAPER TITLE: Coupling of severe climate change and mass extinction influences biogeographic homogenization in deep time

ABSTRACT: Geologically rapid changes in global biogeography are hypothesized to have
6 environmental and ecological drivers, but their relative contributions and potential interactions
7 remain untested. Using interval-to-interval changes in pairwise biogeographic similarity of
8 marine invertebrate communities across the Phanerozoic as a measure of biogeographic change,
9 we assessed whether intervals with high extinction intensity, substantial temperature change, or
10 both were associated with taxonomic homogenization, which is a pattern of substantial increases
11 in the taxonomic similarity between communities across the globe. The end-Permian and first
12 pulse of the Late Ordovician mass extinctions are the only events to result in global taxonomic
13 homogenization that stands out from background conditions. These events represent the most
14 taxonomically severe extinctions and rank among the most sustained episodes of global
15 temperature forcing in the Phanerozoic. In contrast, no measurable shift in global compositional
16 similarity was detected in background intervals or in periods where either pronounced global
17 temperature forcing or mass extinction occurred without the other. Global homogenization
18 appears to require a combination of elevated taxonomic loss and rapid climate change.

PUBLICATION INFORMATION: Copyright (c) 2026 by the authors: a Creative Commons Attribution NonCommercial License 4.0 (CC BY-NC)

GENERAL INFORMATION

1. Title of Datasets: Scotese_intervalT.csv


2. Author Information: Anonymous

3. Date of last time code was run: 2026-08-14

6. License information: CC-BY 4.0

7. DOI for data and code repository: DOI 10.5281/zenodo.18224666. 


DATA & FILE OVERVIEW

1. File List: 

Data
Scotese_intervalT.csv: csv file containing global average temperature data in million-year intervals 
(from Scotese et al., 2021) and averaged for each age for this study.

Code
01_pbdb_download_new.R: Code for downloading fossil occurrence data from the Paleobiology Database
index.html: html file containing all codes, figures, and analyses related to the study and accessible regardless of reader's familiarity with R.
index.qmd:  Quarto markdown containing all code used in this analysis and used to generate the index.html file.


2. Relationship between files, if important: 
01_pbdb_download_new.Ris the R code used to download the occurrence data.
index.qmd is used afterwards for everything else.

4. Additional related data collected that was not included in the current data package: N/A

5. Are there multiple versions of the dataset? No


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data:
   Fossil occurrence data is from the Paleobiology Database and is attributed to the curators and original collectors of that data.
   Temperature data is from Scotese et al. (2021) and from Judd et al. (2024).
   Full citations are in the manuscript.

3. Methods for processing the data: 
Data were simulated using the index.qmd R code.

4. Instrument- or software-specific information (including package versions) needed to interpret the data: 

R version 4.5.2 (2025-10-31)
Platform: aarch64-apple-darwin20
Running under: macOS Tahoe 26.3

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] ggpubr_0.6.2            downloadthis_0.5.0      icosa_0.12.0            rgplates_0.6.1         
 [5] fossilbrush_1.0.6       piggyback_0.1.5         conflicted_1.2.0        magick_2.9.1           
 [9] divDyn_0.8.3            divvy_1.0.1             boot_1.3-32             marelac_2.1.11         
[13] shape_1.4.6.1           scales_1.4.0            cmocean_0.3-2           rnaturalearthdata_1.0.0
[17] rnaturalearth_1.1.0     ggrepel_0.9.8           biooracler_1.0.0        marmap_1.0.12          
[21] rerddap_1.3.0           car_3.1-3               carData_3.0-5           ggtext_0.2.0           
[25] stars_0.7-2             abind_1.4-8             broom_1.0.13            sf_1.1-2               
[29] CoordinateCleaner_3.0.1 robis_2.12.0            patchwork_1.3.2         pROC_1.19.0.1          
[33] reghelper_1.1.2         terra_1.9-46            ggcorrplot_0.3.0        lubridate_1.9.4        
[37] forcats_1.0.1           stringr_1.6.0           dplyr_1.1.4             purrr_1.2.1            
[41] readr_2.1.5             tidyr_1.3.1             tibble_3.3.0            ggplot2_4.0.3          
[45] tidyverse_2.0.0        

loaded via a namespace (and not attached):
 [1] RColorBrewer_1.1-3  rstudioapi_0.17.1   jsonlite_2.0.0      magrittr_2.0.4      farver_2.1.2       
 [6] ragg_1.5.0          vctrs_0.7.2         memoise_2.0.1       hoardr_0.5.5        rstatix_0.7.3      
[11] htmltools_0.5.8.1   curl_7.0.0          raster_3.6-32       Formula_1.2-5       KernSmooth_2.23-26 
[16] htmlwidgets_1.6.4   plyr_1.8.9          cachem_1.1.0        commonmark_2.0.0    whisker_0.4.1      
[21] igraph_2.2.1        lifecycle_1.0.4     pkgconfig_2.0.3     Matrix_1.7-4        R6_2.6.1           
[26] fastmap_1.2.0       rbibutils_2.4       digest_0.6.37       textshaping_1.0.4   crosstalk_1.2.2    
[31] RSQLite_3.53.3      labeling_0.4.3      timechange_0.3.0    gdistance_1.6.5     httr_1.4.7         
[36] compiler_4.5.2      proxy_0.4-27        bit64_4.6.0-1       withr_3.0.2         S7_0.2.0           
[41] backports_1.5.0     DBI_1.3.0           ggsignif_0.6.4      MASS_7.3-65         rappdirs_0.3.3     
[46] gsw_1.2-0           leaflet_2.2.3       classInt_0.4-11     oai_0.4.0           tools_4.5.2        
[51] units_1.0-0         mapedit_0.8.0       otel_0.2.0          rgbif_3.8.3         glue_1.8.0         
[56] stringdist_0.9.15   gridtext_0.1.6      grid_4.5.2          reshape2_1.4.4      generics_0.1.4     
[61] gtable_0.3.6        tzdb_0.5.0          class_7.3-23        data.table_1.18.2.1 hms_1.1.4          
[66] sp_2.2-0            xml2_1.4.1          utf8_1.2.6          pillar_1.11.1       markdown_2.0       
[71] vroom_1.6.6         lattice_0.22-7      bit_4.6.0           oce_1.8-4           tidyselect_1.2.1   
[76] pbapply_1.7-4       knitr_1.50          litedown_0.9        crul_1.6.0          xfun_0.60          
[81] adehabitatMA_0.3.17 stringi_1.8.7       lazyeval_0.2.2      evaluate_1.0.5      codetools_0.2-20   
[86] httpcode_0.3.0      seacarb_3.4.1       SolveSAPHE_2.1.0    cli_3.6.5           Rdpack_2.6.4       
[91] systemfonts_1.3.1   Rcpp_1.1.2          parallel_4.5.2      blob_1.2.4          e1071_1.7-16       
[96] ncdf4_1.24          crayon_1.5.3        geosphere_1.6-5     rlang_1.1.7        


DATA-SPECIFIC INFORMATION FOR: 

Scotese_intervalT.csv
1. Number of variables: 8

2. Number of cases/rows: 543

3. Variable List: 
ScoteseAge: interval at which global average temperature is reported by Scotese et al. (2021)
GAT: Global Average Temperature corresponding with ScoteseAge
T_change_1: Amount of change in that millionth year since the millionth year before it
early_interval: geologic age name
Age: year corresponding to geologic age name
ave_T: absolute GAT averaged for the duration of that age
T_change: average change in GAT since the age before it
age_length: temporal duration of the age

5. Missing data codes: NA

