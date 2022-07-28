# publications
Here you will find the Supplementary Material, programs, and in-house scripts of my publications (for most of them).


___

Table of Contents
-----------------

1. [Supplementary Material for PhD thesis (*updating files*)](#pdhsm)
2. [Supplementary Material by publication (*in preparation*)](#pubsm)
3. [Useful in-house scripts (*updating files*)](#scripts)


## Supplementary Material for PhD thesis


**(a) Datasets compilation for the 461 eukaryotic species used in this study:** \
(1) List of all genome projects used in this study (excell file). [Download here]() \
(2) References for cellular definitions and phylogenetic relationships (excell file). [Download here]() \
(3) Overview of the sequence features annotated acrosss 461 eukaryotic genome projects, as calculated by `GenomeContent` (excell file). [Download here]() \
(4) Benchmarking of `GenomeContent` and `AGAT` programs with four eukaryotic genomes (excell file). [Download here]()


**(b) Statistical descriptors of genome-wide features and other genome-based estimators for 461 eukaryotic species, as calculated with the `GenomeContent` program:** \
(1) Description of the genowe-wide features (variables) included in the file "SMO_GenomeFeatures_descriptors_eukaryotes.xlsx" (text file). [description_variables_instudy.txt](https://github.com/ilozada/publications/files/9142262/description_variables_instudy.txt) \
(2) Dataset of statistical descriptors of genome-wide features for 461 eukaryotic genomes (excell file). \
(3) Summary statistics of selected genome-wide features from protein-coding genes for selected lineages (excell file). [SMO_GenomeFeatures_by_TaxaDatasets.xlsx](https://github.com/ilozada/publications/files/9142748/SMO_GenomeFeatures_by_TaxaDatasets.xlsx) \
(4) Coefficients of variation for genome-wide features across different taxa datasets (excell file).  \
(5) Fraction of placeholders (Ns and Xs sequences) covering the total assembled genome (text file): [genome_nts-placeholders_composition.txt](https://github.com/ilozada/publications/files/9127990/genome_nts-placeholders_composition.txt) \
(6) The excess/deficit of the intron length distributions modulo 3 estimated (as suggested by Roy and Penny, 2007: PMID:17617639) for more than the 461 gene annotations included in this study (text file): [intron_3n_quality_501sps.txt](https://github.com/ilozada/publications/files/9127855/intron_3n_quality_501sps.txt) \
(7) Figures showing the results of (5) and (6) analyses (pdf file). [SMO_quality_genomes_annotations.pdf](https://github.com/ilozada/publications/files/9150301/SMO_quality_genomes_annotations.pdf) \
(8) Permutation tests for the Jaccard index estimations to evaluate the repeat contribution to intron and exon sizes (excell file).


**(c) Data and additional results from the `ceRNA motif pipeline`:** \
(1) Summary of the genome datasets and of the 40 non-redundant miRNA:lincRNAs binding sequences analyzed with our ceRNA motif pipeline (excell file). [SMO_knownTMs_Genomes_Datasets.xlsx](https://github.com/ilozada/publications/files/9155391/SMO_knownTMs_Genomes_Datasets.xlsx) \
(2) ceRNA literature-directed research and predicted target mimics (TMs) motifs that were eliminated with the `ceRNA motif pipeline` (pdf file). [SMO_TMs-research_FigureS1-S4.pdf](https://github.com/ilozada/publications/files/9150871/SMO_TMs-research_FigureS1-S4.pdf) \
(3) Summary results of the predicted TMs motifs from the `ceRNA motif pipeline` (excell file). [SMO_predictedTMmotifs_ceRNApipeline.xlsx](https://github.com/ilozada/publications/files/9155432/SMO_predictedTMmotifs_ceRNApipeline.xlsx) \
(4) Raw results from the mapping of TM motifs across transcriptomic data (compressed text files): \
    --- Results from the psRNATarget v1.0 program: [SuppData2_psRNATarget_TMmotifs.zip](https://github.com/ilozada/publications/files/9150977/SuppData2_psRNATarget_TMmotifs.zip) \
    --- Results from the TAPIR v1.2 program: [SuppData3_TAPIR_TMmotifs.zip](https://github.com/ilozada/publications/files/9151034/SuppData3_TAPIR_TMmotifs.zip)


**(d) Phylogenetically controlled linear regressions:** \
(1) Estimates of phylogenetic inertia with different tree topologies (excell file). \
(2) Regressions with the Ordinary Least-Squares (OLS) model (excell file). \
(3) Regressions with the Phylogenetic Generalized Least Squares (PGLS) model (excell file). \
(4) Regressions with the Phylogenetically Independent Contrasts (PICs) model (excell file). \
(5) Estimates of Log Bayes Factors with the PGLS and PIC models and different tree topologies (excell file).


**(e) Principal Component Analyses (PCA) analyses for 7 intron-based features and 15 genome-based features, and multicellular complexity:** \
(1) Cronbach's test for 7 intron-based features and 15 genome-based features used to calculate the PCA analyses (excell file). [SMO_CronbrachTest_PCAs.xlsx](https://github.com/ilozada/publications/files/9176642/SMO_CronbrachTest_PCAs.xlsx) \
(2) Phylogenetic PCAs with phylogenetically independent contrasts for: (i) 7 intron-based features and 15 genome-based features, (ii) different tree topologies, and (iii) genome size estimations (excell file). [SMO_PhyloPCAs.xlsx](https://github.com/ilozada/publications/files/9173969/SMO_PhyloPCAs.xlsx) \
(3) Comparative PCAs for 15 genome-based features and different genome size estimations (excell file). [SMO_comparativePCAs.xlsx](https://github.com/ilozada/publications/files/9174913/SMO_comparativePCAs.xlsx)


**(f) Tree topologies for the 461 eukaryotic species used in this study:**

(1) Results of the "dissimilarity metrics" used to calculate differences among the four alternative tree topologies of the 461 eukaryotes analyzed in this study. [SMO_ComparativeMetricsTrees.xlsx](https://github.com/ilozada/publications/files/9189488/SMO_ComparativeMetricsTrees.xlsx)


(2) Reference tree topology (a supertree created by synthesizing phylogeny and taxonomic classification): \
--- [reference_eukaryote_phylogeny.pdf (pdf file)](https://github.com/ilozada/publications/files/9126957/reference_eukaryote_phylogeny.pdf) \
--- [reference_eukaryote_phylogeny.nex (nexus file)](https://github.com/ilozada/publications/files/9126964/reference_eukaryote_phylogeny_nexus.txt) \
--- [reference_eukaryote_phylogeny.nwk (newick file)](https://github.com/ilozada/publications/files/9127051/reference_eukaryote_phylogeny_newick.txt)


(3) NCBI taxonomy-based tree topology (that is forced to be a fully resolved bifurcating phylogeny): \
--- [ncbi-taxonomy_tree_fully-bifurcated.pdf (pdf file)](https://github.com/ilozada/publications/files/9127059/ncbi-taxonomy_tree_fully-bifurcated.pdf) \
--- [ncbi-taxonomy_tree_fully-bifurcated_nexus.txt (nexus file)](https://github.com/ilozada/publications/files/9127060/ncbi-taxonomy_tree_fully-bifurcated_nexus.txt) \
--- [ncbi-taxonomy_tree_fully-bifurcated_newick.txt (newick file)](https://github.com/ilozada/publications/files/9127061/ncbi-taxonomy_tree_fully-bifurcated_newick.txt)

(4) NCBI taxonomy-based tree topology (that is allowed to incorporate hard and soft polytomies): \
--- [ncbi-taxonomy_tree_polytomies.pdf (pdf file)](https://github.com/ilozada/publications/files/9127077/ncbi-taxonomy_tree_polytomies.pdf) \
--- [ncbi-taxonomy_tree_polytomies_nexus.txt (nexus file)](https://github.com/ilozada/publications/files/9127078/ncbi-taxonomy_tree_polytomies_nexus.txt) \
--- [ncbi-taxonomy_tree_polytomies_newick.txt (newick file)](https://github.com/ilozada/publications/files/9127079/ncbi-taxonomy_tree_polytomies_newick.txt)

(5) Tree topology based on (PFAM) protein domain content (and corrected for protein-content biases derived from differences in genome size and lifestyles) \
 --- [protein-domain_content_phylogeny.pdf (pdf file)](https://github.com/ilozada/publications/files/9127735/protein-domain_content_phylogeny.pdf) \
 --- [protein-domain_content_phylogeny_nexus.txt (nexus file)](https://github.com/ilozada/publications/files/9127757/protein-domain_content_phylogeny_nexus.txt) \
 --- [protein-domain_content_phylogeny_newick.txt (newick file)](https://github.com/ilozada/publications/files/9127759/protein-domain_content_phylogeny_newick.txt)

