# Beyond_Mean_TDT_2025
Code and associated data corresponding to the manuscript "Moving beyond mean thermal death times to assess organismal responses to stressful temperatures"

File Descriptions:

plos.Bio_supp_code_allfigs.Rmd: This file contains all code required to reproduce all analyses and figures in the paper. Code is organized in sections with a chunk to clear the directory at the beginning of each section. Run code in order from each of these chunks to produce desired figures.
	Required files: Jorgenson_Static.csv, Niko_temps_csvs.zip
	Packages used: stats (version 4.4.1), tidyverse (version 2.0.0), eha (version 2.11.5), gridExtra (version 2.3), patchwork (version 1.3.0), flexsurv (version 2.3.2), viridis (version 0.6.5), RColorBrewer (version 1.1-3), survival (version 3.6-4), ggsurvfit (version 1.1.0), survminer (version 0.5.0), ggplotify (version 0.1.2)
	R version: 4.4.1

Jorgenson_Static.csv: Survival data for 11 species of Drosophila under constant temperature conditions. Obtained from Jørgensen et al. 2019.

Niko_temps_csvs.zip: contains files for temperature and survival data for Drosophila melanogaster. Corresponds to figure 4. Collected and shared by the authors of Jørgensen et al 2021.
Contents: 
          Niko_temps_exp1.csv, Niko_temps_exp2, Niko_temps_exp3: Fluctuating stressful temperature data corresponding to the survival data in  Nikolaj_TDT_formatted.csv
          Nikolaj_TDT_raw.csv: Constant temperature knockdown data for D. melanogaster from the same population as Nikolaj_TDT_formatted.csv. Used to train fluctuationg temperature knockdown models.
          Nikolaj_TDT_formatted.csv: FLuctuating temperature knockdown data for D. melanogaster corresponding to the temperature conditions in Niko_temps_exp1-3. 



