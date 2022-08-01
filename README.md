# publications
Here you will find the Supplementary Material, programs, and in-house scripts of my publications (for most of them).


___

Table of Contents
-----------------

1. [Supplementary Material for PhD thesis (*updating files*)](#pdhsm)
2. [Useful in-house scripts (*updating files*)](#scripts)
3. [Supplementary Material by publication (*in preparation*)](#pubsm)


## Supplementary Material for PhD thesis (*updating files*)


**(a) Datasets compilation for the 461 eukaryotic species used in this study:** \
(1) List of all genome projects used in this study (excell file). [Download here]() \
(2) References for cellular definitions and phylogenetic relationships (excell file). [Download here]() \
(3) Overview of the sequence_features (based on the Sequence Ontology project: https://github.com/The-Sequence-Ontology/SO-Ontologies) from the gene annotation files (GTF*/GFF*) of 461 eukaryotic genome projects, as calculated by `GenomeContent` (excell file). [Download here]() \
(4) Benchmarking of `GenomeContent` and `AGAT` programs with four eukaryotic genomes (excell file). [SMO_Benchmark_GenomeContent.xlsx](https://github.com/ilozada/publications/files/9229572/SMO_Benchmark_GenomeContent.xlsx)


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
(1) Estimates of phylogenetic inertia with different tree topologies at the broadest phylogenetic scale (461 species) (excell file). \
(2) Regressions with the Ordinary Least-Squares (OLS) model at the broadest phylogenetic scale (461 species), with different genome size estimations (excell file). [SMO_OLS_regressions.xlsx](https://github.com/ilozada/publications/files/9229195/SMO_OLS_regressions.xlsx) \
(3) Regressions with the Phylogenetic Generalized Least Squares (PGLS) model at the broadest phylogenetic scale (461 species), with different tree topologies and genome size estimations (excell file). [SMO_PGLS_regressions.xlsx](https://github.com/ilozada/publications/files/9227593/SMO_PGLS_regressions.xlsx) \
(4) Regressions with the Phylogenetically Independent Contrasts (PICs) model at the broadest phylogenetic scale (461 species), with different tree topologies and genome size estimations (excell file). \
(5) Estimates of Log Bayes Factors with the PGLS and PIC models and different tree topologies at the broadest phylogenetic scale (461 species) (excell file). \
(6) Regressions with the PGLS model at the local phylogenetic scale (31 different datasets) (text files): \
    --- Reference supertree topology: \
    --- NCBI taxonomy-based tree topology (fully bifurcated): \
    --- NCBI taxonomy-based tree topology (with hard and soft polytomies): \
    --- Tree topology based on protein FPAM-domain content:

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



## Useful in-house scripts (*updating files*)

- **Parallel computing: example of job submission to a Sun Grid Engine scheduler** \
To run a job to a cluster controlled by the Sun Grid Engine scheduler, a shell script has to be used. Here is an example to run the `GenometriCorr` package for 134 genomes (listed on the file: script_ARRAY_JOB.genometricorr.metazoa.txt) on multiple CPUs for a long time:

```terminal
#!/bin/sh

#$ -S /bin/bash
#$ -N geo_metaz
#$ -cwd
#$ -q normal.q
#$ -t 1-134
#$ -e /scr/k70/ilozada/qsub_scripts/repeats/tmp/error.$JOB_ID
#$ -o /scr/k70/ilozada/qsub_scripts/repeats/tmp/salida.$JOB_ID
#$ -v PATH=/homes/bierdepot/ilozada/programs2/lib64/R/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:$PATH

SEEDFILE=/scr/k70/ilozada/qsub_scripts/repeats/genometricorr/script_ARRAY_JOB.genometricorr.metazoa.txt
SEED=$(cat $SEEDFILE | head -n $SGE_TASK_ID | tail -n 1)
$SEED

# Useful SLURM commands:
#	- qsub    : submit a batch job to the specified queue:   qsub -q queue_name job_script
#   - qstat   : list jobs & list jobs for users:             qstat -u username
#	- qdel    : delete (cancel) a job:                       qdel jobID 
#	            cancel multiple jobs:                        qdel jobID1, jobID2, jobID3 ...
#	- qhold   : hold a job:                                  qhold jobID
# ---------------------------------------------------------------------------------------------- 

```


- **Parallel computing: example of job submission to a Slurm workload manager** \
To run a job to a cluster controlled by the Slurm workload manager, a batch script has to be used. Here is an example to run the `hmmscan` program for 59 genomes (listed on the file: script_ARRAY_JOB.metazoa.new2020.pfams32.txt) on multiple CPUs for a long time: **slurm.hmmscan.metazoa.sbatch**

```terminal
#!/bin/bash

#SBATCH --account=ilozada
#SBATCH --partition=main
#SBATCH --cpus-per-task=1
#SBATCH --threads-per-core=2
#SBATCH --job-name=pfamMetz
#SBATCH --mem=4gb
#SBATCH --time=2-00:00
#SBATCH --array=1-59%59
#SBATCH --ntasks=1
#SBATCH --error=pfammetazoa_%j.stderr-%A_%a.log
#SBATCH --output=pfammetazoa_%j.stdout-%A_%a.log

SEEDFILE=/scr/k70/ilozada/qsub_scripts/pfam/script_ARRAY_JOB.metazoa.new2020.pfams32.txt
SEED=$(cat $SEEDFILE | head -n $SLURM_ARRAY_TASK_ID | tail -n 1)
$SEED

# Useful SLURM commands:
#	- sbatch  : submit a job in slurm. Syntaxis:   sbatch mySLURM_script.sbatch [MAIN]
#   - squeue  : list jobs & list jobs for users:   squeue --user=ilozada        [MAIN]
#	- scancel : cancel a job. Syntaxis:            scancel your_jobID           [MAIN]
#	            cancel multiple jobs:              scancel jobID1, jobID2, jobID3 ...
#	- sstat   : shows job status. Syntaxis:        sstat --jobs=jobID
#	- sacct   : shows past jobs.  Syntaxis:        sacct --jobs=jobID
#	- scontrol: control jobs for suspend, hold or pulling information on jobs. 
#	            Syntaxis:   scontrol [suspend,hold,release,resume,show] jobID
# ---------------------------------------------------------------------------------------------- 

```
