# Single-cell-data-visualization-tools
Collection of single-cell data visualization tools from https://github.com/mdozmorov/scRNA-seq_notes

- [Kana](https://www.jkanche.com/kana/) - single-cell analysis in the browser, by Jayaram Kancherla (@jkanche), Aaron Lun (@LTLA). Input - 10X genomics CellRanger's output, matrix or .h5 files. Preprocessing (removal of low-quality cells, Normalization and log-transformation, Modelling of the mean-variance trend across genes), PCA, Clustering (t-SNE/UMAP), Marker detection, custom cluster definition and marker analysis. Works with scATAC-seq data. [GitHub](https://github.com/jkanche/kana), Tweet.

- [cellxgene](https://github.com/chanzuckerberg/cellxgene) - An interactive exploratory visualization tool for single-cell transcriptomics data, web and desktop versions. Input - matrix-form datasets, metadata, pre-computed embeddings/clustering. Compatible with Seurat, Scanpy, Bioconductor, scVI [GitHub](https://github.com/chanzuckerberg/cellxgene)

> Megill, Colin, Bruce Martin, Charlotte Weaver, Sidney Bell, Lia Prins, Seve Badajoz, Brian McCandless, et al. **"Cellxgene: A Performant, Scalable Exploration Platform for High Dimensional Sparse Matrices"** https://doi.org/10.1101/2021.04.05.438318 Preprint. Systems Biology, April 6, 2021.

- [iCellR](https://github.com/rezakj/iCellR) - Single (i) Cell R package (iCellR) is an interactive R package to work with high-throughput single cell sequencing technologies (i.e scRNA-seq, scVDJ-seq and CITE-seq).
 
> Khodadadi-Jamayran, Alireza, Joseph Pucella, Hua Zhou, Nicole Doudican, John Carucci, Adriana Heguy, Boris Reizis, and Aristotelis Tsirigos. "ICellR: Combined Coverage Correction and Principal Component Alignment for Batch Alignment in Single-Cell Sequencing Analysis" https://www.biorxiv.org/content/10.1101/2020.03.31.019109v1.full BioRxiv, April 1, 2020

- [Cerebro](https://github.com/romanhaa/Cerebro) - interactive scRNA-seq visualization from a Seurat object (v2 or 3), dimensionality reduction, clustering, identification and visualization of marker genes, enriched pathways (EnrichR), signatures (MSigDb), expression of individual genes. [cerebroPrepare](https://github.com/romanhaa/cerebroPrepare) R package saves the Seurat object, to be visualized with [cerebroApp Shiny app](https://github.com/romanhaa/cerebroApp). Standalone and Docker versions are available. [GitHub](https://github.com/romanhaa/Cerebro).

> Hillje, Roman, Pier Giuseppe Pelicci, and Lucilla Luzi. "Cerebro: Interactive Visualization of ScRNA-Seq Data" https://doi.org/10.1093/bioinformatics/btz877 Bioinformatics, 1 April 2020

- [iS-CellR](https://github.com/immcore/iS-CellR) - a Shiny app for scRNA-seq analysis. Can be insalled locally, run from GitHub, Docker. Input - count matrix. Filtering, normalization, dimensionality reduction, clustering, differential expression, co-expression, reports.

> Patel, Mitulkumar V. "IS-CellR: A User-Friendly Tool for Analyzing and Visualizing Single-Cell RNA Sequencing Data" https://doi.org/10.1093/bioinformatics/bty517 Bioinformatics 34, no. 24 (December 15, 2018)

- [iSEE](https://github.com/kevinrue/iSEEWorkshop2019) - Shiny app for interactive visualization of SummarizedExperiment scRNA-seq objects. [GitHub](https://github.com/csoneson/iSEE), [RNA-seq blog post](https://www.rna-seqblog.com/isee-an-interactive-shiny-based-graphical-user-interface-for-exploring-data-stored-in-summarizedexperiment-objects/), [Workshop](https://github.com/kevinrue/iSEEWorkshop2019).

> Rue-Albrecht, Kevin, Federico Marini, Charlotte Soneson, and Aaron T.L. Lun. "ISEE: Interactive SummarizedExperiment Explorer" https://doi.org/10.12688/f1000research.14966.1 F1000Research 7 (June 14, 2018)

- [SPRING](https://github.com/AllonKleinLab/SPRING_dev) - a pipeline for data filtering, normalization and visualization using force-directed layout of k-nearest-neighbor graph. [Web-based](https://kleintools.hms.harvard.edu/tools/spring.html) (10,000 cells max) and [GitHub](https://github.com/AllonKleinLab/SPRING_dev).

> Weinreb, Caleb, Samuel Wolock, and Allon M. Klein. "SPRING: A Kinetic Interface for Visualizing High Dimensional Single-Cell Expression Data" https://doi.org/10.1093/bioinformatics/btx792 Bioinformatics (Oxford, England) 34, no. 7 (April 1, 2018)

- [Granatum](http://garmiregroup.org/granatum/app) - web-based scRNA-seq analysis. list of modules, including plate merging and batch-effect removal, outlier-sample removal, gene-expression normalization, imputation, gene filtering, cell clustering, differential gene expression analysis, pathway/ontology enrichment analysis, protein network interaction visualization, and pseudo-time cell series reconstruction. [Twitter](https://twitter.com/GarmireGroup/status/1185269818015940609).

> Zhu, Xun, Thomas K. Wolfgruber, Austin Tasato, Cédric Arisdakessian, David G. Garmire, and Lana X. Garmire. "Granatum: A Graphical Single-Cell RNA-Seq Analysis Pipeline for Genomics Scientists" https://doi.org/10.1186/s13073-017-0492-3 Genome Medicine 9, no. 1 (December 2017).

- [SCope](https://github.com/aertslab/SCope) - Fast visualization tool for large-scale and high dimensional single-cell data in .loom format. R and Python scripts for converting scRNA-seq data to .loom format.

- [singleCellTK](https://bioconductor.org/packages/singleCellTK/) - R/Shiny package for an interactive scRNA-Seq analysis. Input, raw counts in SingleCellExperiment. Analysis: filtering raw results, clustering, batch correction, differential expression, pathway enrichment, and scRNA-Seq study design.

- [scDataviz](https://github.com/kevinblighe/scDataviz) - single cell data vizualization and downstream analyses, by Kevin Blighe

- [scOrange](https://singlecell.biolab.si/) - visual pipeline builder for an in-depth analysis and visualization of scRNA-seq data. Works with 10X data, tab-delimited. Filtering, preprocessiong, differential gene expression, marker analysis, enrichment analysis, batch removal, clustering, tSNE. [Screenshots](https://singlecell.biolab.si/screenshots/), [Short video tutorials](https://www.youtube.com/playlist?list=PLmNPvQr9Tf-a4MrEG5thq3qzlkrF5NFbC). Python-based, Conda-installable. [GitHub](https://github.com/biolab/orange3-single-cell)

- [scCustomize](https://github.com/samuel-marsh/scCustomize) - an R package, Collection of functions created and/or curated to aid in the visualization and analysis of single-cell data. Extends Seurat, Liger visualization, helper functions to enhance analysis of Seurat objects.

- [UCSC Single Cell Browser](https://github.com/maximilianh/cellBrowser) - Python pipeline and Javascript scatter plot library for single-cell datasets. Pre-process an expression matrix by filtering, PCA, nearest-neighbors, clustering, t-SNE and UMAP and formats them for cbBuild. [Demo that includes several landmark datasets](https://cells.ucsc.edu/)
