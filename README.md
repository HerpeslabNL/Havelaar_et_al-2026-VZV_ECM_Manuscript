# R scripts used in Havelaar _et al._ VZV ECM manuscript
Bullet Title: 
- VZV RNA-seq and CUT&RUN Analysis Scripts
- R Markdown scripts for gene-expression analysis and visualization of varicella-zoster virus (VZV) sequencing data.

## Scripts

- **1.Padj_manual.Rmd** — Extracts DESeq2 contrasts and calculates Benjamini–Hochberg-adjusted p-values.
- **2.PCA.Rmd** — Generates RNA-seq principal component analysis (PCA) plots.
- **3.VolcanoPlot.Rmd** — Plots differential gene expression, highlighting extracellular matrix (ECM) genes and CCL2.
- **4.GO_Slim_dotplot.Rmd** — Performs GO Slim over-representation analysis (BP, CC, MF), exporting dotplots and tables.
- **5.GO_heatmaps.Rmd** — Creates expression heatmaps for differentially expressed genes in selected GO terms.
- **6.Neuronal_Markers.Rmd** — Compares neuronal and cell-cycle marker expression in undifferentiated and differentiated HD10.6 cells.
- **7.VZV_coverage_map.Rmd** — Plots strand-specific VZV genome coverage alongside gene annotations.

**Usage:** Adjust input paths, sample names, and settings as needed. Required R packages are listed in the scripts.
