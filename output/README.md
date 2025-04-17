* `mag_pathway_details/` contains csv files detailing certain metabolic pathway KOs and linking them to specific MAG taxa
* `adata_var.csv` contains metadata and stats related to each MAG
* `filtered_ad_var.csv` is the same format but only contains MAGs with overall median relative abundance greater than 0.01% based on CoverM read mapping
* `mag_class_dram_df_FILTERED.csv` contains average metabolic module completion fraction for the relative abundance filtered MAGs grouped at the taxonomic class level.
* `depth_correlated_genes.csv` contains KOs that are significantly correlated with soil depth (defined as FDR corrected p < 0.05)
* `kegg_modules_stats.csv` details the spearman correlation and kruskal-wallis stats associated with the KEGG modules. Based on overall KO estimated gene copies.
