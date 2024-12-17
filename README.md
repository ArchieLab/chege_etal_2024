# Eukaryotic composition across seasons and social groups in the gut microbiota of wild baboons

Animals coexist with complex microbiota, including bacteria, viruses, and eukaryotes (e.g., fungi, protists, and helminths). While the composition of bacterial and viral components of animal microbiota are increasingly well understood, eukaryotic composition remains neglected. Here we characterized eukaryotic diversity in the microbiomes in wild baboons and tested the degree to which eukaryotic community composition was predicted by host social group membership, sex, age, and season of sample collection.

Here, **we analyzed 75 fecal samples collected between 2012 and 2014 from 73 wild baboons in the Amboseli ecosystem in Kenya to test the effects of social group membership, seasonality, host sex, and age**. DNA from these samples was subjected to shotgun metagenomic sequencing, revealing members of the kingdoms Protista, Chromista, and Fungi in 90.7%, 46.7%, and 20.3% of samples, respectively. Social group membership explained 11.2% of the global diversity in gut eukaryotic species composition, but we did not detect statistically significant effect of season, host age, and host sex. Across samples, the most prevalent protists were Entamoeba coli (74.66% of samples), Enteromonas hominis (53.33% of samples), and Blastocystis subtype 3 (38.66% of samples), while the most prevalent fungi included Pichia manshurica (14.66% of samples), and Ogataea naganishii (6.66% of samples).  

Our results highlight the relevance of Protista, Chromista, and Fungi as integral members of the gut microbiome of wild baboons. More work on eukaryotic members of primate gut microbiota is essential for primate health monitoring and management strategies.

# Workflow
First, we analysed the **eukaryotic composition across all samples**, from both sets of data.

`bin/Rmarkdown scr/combined/Heatmap_merged.Rmd`

We then investigated the effect of **social group membership** on the Amboseli baboons gut eukaryotic composition:

`bin/Rmarkdown scr/social_group/Heatmap_socialGroup.Rmd`

`bin/Rmarkdown scr/social_group/social_group_analysis.Rmd`

Finally, we assessed the impact of **seasonality** on the eukaryotic gut microbiome composition. 

`bin/Rmarkdown scr/season/Heatmap_season.Rmd`

`bin/Rmarkdown scr/season/season_analysis.Rmd`

# Notes
R version used: v4.3.3. 
Raw data is available on NCBI under the accession BioProject IDs: PRJNA271618 (Tung et al. 2015) and PRJEB81717 (novel data presented in this study).
For any information or request, please contact the corresponding authors: mchege89@gmail.com; earchie@nd.edu.
