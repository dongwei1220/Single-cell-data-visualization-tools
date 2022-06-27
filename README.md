# Single-cell-data-visualization-tools
Collection of single-cell data visualization tools from https://github.com/mdozmorov/scRNA-seq_notes

- iCellR - Single (i) Cell R package (iCellR) is an interactive R package to work with high-throughput single cell sequencing technologies (i.e scRNA-seq, scVDJ-seq and CITE-seq).

Khodadadi-Jamayran, Alireza, Joseph Pucella, Hua Zhou, Nicole Doudican, John Carucci, Adriana Heguy, Boris Reizis, and Aristotelis Tsirigos. “ICellR: Combined Coverage Correction and Principal Component Alignment for Batch Alignment in Single-Cell Sequencing Analysis,” BioRxiv, April 1, 2020

- Cerebro - interactive scRNA-seq visualization from a Seurat object (v2 or 3), dimensionality reduction, clustering, identification and visualization of marker genes, enriched pathways (EnrichR), signatures (MSigDb),  expression of individual genes. cerebroPrepare R package saves the Seurat object (https://github.com/romanhaa/cerebroPrepare), to be visualized with cerebroApp Shiny app (https://github.com/romanhaa/cerebroApp). Standalone and Docker versions are available. Main repo: https://github.com/romanhaa/Cerebro

Hillje, Roman, Pier Giuseppe Pelicci, and Lucilla Luzi. “Cerebro: Interactive Visualization of ScRNA-Seq Data.” Preprint. Bioinformatics, May 8, 2019.

- iS-CellR - a Shiny app for scRNA-seq analysis. Can be insalled locally, run from GitHub, Docker. Input - count matrix. Filtering, normalization, dimensionality reduction, clustering, differential expression, co-expression, reports. https://github.com/immcore/iS-CellR

Patel, Mitulkumar V. “IS-CellR: A User-Friendly Tool for Analyzing and Visualizing Single-Cell RNA Sequencing Data.” Bioinformatics 34, no. 24 (December 15, 2018)

- iSEE - Shiny app for interactive visualization of SummarizedExperiment scRNA-seq objects. https://github.com/csoneson/iSEE, https://www.rna-seqblog.com/isee-an-interactive-shiny-based-graphical-user-interface-for-exploring-data-stored-in-summarizedexperiment-objects/, https://github.com/kevinrue/iSEEWorkshop2019

Rue-Albrecht, Kevin, Federico Marini, Charlotte Soneson, and Aaron T.L. Lun. “ISEE: Interactive SummarizedExperiment Explorer.” F1000Research 7 (June 14, 2018)

- SPRING - a pipeline for data filtering, normalization and visualization using force-directed layout of k-nearest-neighbor graph. Web-based (10,000 cells max) https://kleintools.hms.harvard.edu/tools/spring.html and GitHub https://github.com/AllonKleinLab/SPRING_dev

Weinreb, Caleb, Samuel Wolock, and Allon M. Klein. “SPRING: A Kinetic Interface for Visualizing High Dimensional Single-Cell Expression Data.” Bioinformatics (Oxford, England) 34, no. 7 (April 1, 2018)

- Granatum - web-based scRNA-seq analysis. list of modules, including plate merging and batch-effect removal, outlier-sample removal, gene-expression normalization, imputation, gene filtering, cell clustering, differential gene expression analysis, pathway/ontology enrichment analysis, protein network interaction visualization, and pseudo-time cell series reconstruction. Twitter, http://garmiregroup.org/granatum/app

Zhu, Xun, Thomas K. Wolfgruber, Austin Tasato, Cédric Arisdakessian, David G. Garmire, and Lana X. Garmire. “Granatum: A Graphical Single-Cell RNA-Seq Analysis Pipeline for Genomics Scientists.” Genome Medicine 9, no. 1 (December 2017).

- singleCellTK - R/Shiny package for an interactive scRNA-Seq analysis. Input, raw counts in SingleCellExperiment. Analysis: filtering raw results, clustering, batch correction, differential expression, pathway enrichment, and scRNA-Seq study design. https://compbiomed.github.io/sctk_docs/articles/v01-Introduction_to_singleCellTK.html

- cellxgene - An interactive explorer for single-cell transcriptomics data. https://chanzuckerberg.github.io/cellxgene/

- UCSC Single Cell Browser - Python pipeline and Javascript scatter plot library for single-cell datasets. Pre-process an expression matrix by filtering, PCA, nearest-neighbors, clustering, t-SNE and UMAP and formats them for cbBuild. Stand-alone app on GitHub, https://github.com/maximilianh/cellBrowser, Demo that includes several landmark datasets

- SCope - Fast visualization tool for large-scale and high dimensional single-cell data in .loom format. R and Python scripts for converting scRNA-seq data to .loom format. https://github.com/aertslab/SCope

- scDataviz - single cell data vizualization and downstream analyses, by Kevin Blighe
