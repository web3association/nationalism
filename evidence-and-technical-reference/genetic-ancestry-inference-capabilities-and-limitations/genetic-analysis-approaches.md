# Genetic analysis approaches

Once genetic data have been collected, statistical, computational and comparative methods can be used to interpret them. Different methods address different questions. Some examine close relationships. Others investigate population similarity, historical admixture or demographic history.



## **Quality control and preprocessing methods**

These are not ancestry analyses by themselves, but they are necessary before reliable ancestry analysis can happen.

* **1. Sample quality control -** Checks whether a DNA sample is usable and whether genotype/sequence quality is high enough. Helps to prevent false ancestry signals caused by bad data, contamination, low coverage or technical errors.
* **2. Variant calling -** Convert raw sequencing reads into identified genetic variants. Helps to create the list of SNPs/indels used for downstream ancestry and lineage analysis.
* **3. Genotype calling -** Assign genotypes at measured SNP sites from chip or sequence data. Helps to produce the AA/AG/GG-style marker data needed for population comparison.
* **4. Phasing -** Estimates which variants are on the same chromosome copy. This is essential for haplotype analysis, chromosome painting, local ancestry and better IBD detection.
* **5. Imputation -** Predict untyped variants using reference panels. Helps to Increase marker density, improving population analyses and fine-scale ancestry inference.
* **6. Relatedness filtering / sample deduplication -** Identify duplicate or closely related samples in datasets. Helps to prevent family clusters from biasing population analyses.
* **7. Ancestry-informative marker selection -** Choose markers that best distinguish populations. Helps to improve efficiency and sometimes clarity of ancestry classification.



## **Comparing people with relatives**

* **Kinship analysis** - Estimates the degree of biological relationship between individuals. Helps with showing whether people are siblings, cousins, or otherwise related, supporting recent ancestral connections.
* **IBD detection** - Finds long DNA segments shared because of recent common ancestry. Helps provide strong evidence of recent biological descent or overlap with a group through shared ancestors.
* **Parentage testing** - Tests whether one individual is the biological parent of another. Helps with confirming direct recent descent and anchors genealogical lineages.
* **Pedigree methods -** Uses genetic relationship data across multiple people to test or reconstruct family-tree structures. Helps with validating genealogical hypotheses, linking multiple relatives into one family network, and checking whether a proposed pedigree is genetically consistent.



## **Tracing one paternal or maternal line**

* **Y-STR matching -** Compares STR markers on the Y chromosome between men. Helps to support paternal-line connections and lineage matching.
* **mtDNA sequence matching -** Compares mitochondrial sequences across individuals. Helps to support maternal-line connections.
* **Y haplogroup assignment -** Places a male Y chromosome into a branching paternal lineage tree. Helps to identify deep paternal ancestry and relationships among paternal lines.
* **mtDNA haplogroup assignment -** Places mitochondrial DNA into a maternal lineage tree. Helps to Identify deep maternal ancestry and maternal-line relationships.
* **Haplogroup phylogeny -** Uses mutations to place lineages on a branching evolutionary tree. Helps to show how paternal or maternal lineages relate to one another and to broader ancestral branches.
* **TMRCA estimation -** Estimates time to the most recent common ancestor for a lineage. Helps to find a date when two Y or mtDNA lineages shared a common ancestor.



## **Compare someone to a population**

* **Principal component analysis (PCA) -** Compresses genome-wide variation into a few axes of genetic similarity. Helps to show which populations an individual clusters near genetically.
* **Multidimensional scaling (MDS) -** Another way to visualise genetic similarity or distance. Similar to PCA, it helps show population structure.
* **Allele-frequency population matching -** Compares an individual’s allele profile with population frequency profiles. Estimates which populations the person most resembles.
* **Genetic distance analysis -** Uses statistical measures of genetic difference or similarity between individuals or populations. Helps identify which populations are genetically closest and quantify relative separation.
* **Fst analysis -** A population differentiation measure. Helps to quantify how distinct two populations are genetically.
* **Cluster analysis -** Groups individuals into data-driven genetic clusters based on overall similarity. Helps reveal population substructure and possible ancestral groupings without requiring known family relationships.
* **Admixture / model-based clustering** — Estimates ancestry proportions by fitting an individual’s genome as a mixture of reference or inferred population clusters. Helps identify mixed ancestry and population structure.
* **Supervised ancestry assignment -** Assigns ancestry using predefined reference groups. Helps when testing fit to known candidate ancestral populations.
* **Admixture dating -** Estimates when different ancestral populations mixed. Helps determine whether shared ancestry is recent or older.



## **Detailed segment-level ancestry**

These methods use linked DNA segments across the genome and are often more powerful than broad marker-frequency methods.

* **Haplotype-based ancestry inference -** Compares long linked blocks of DNA to reference populations. Helps with distinguishing nearby or subtly different populations.
* **Chromosome painting -** “Paints” each chromosome as copied from various reference populations. Helps with showing which parts of the genome resemble which ancestral groups.
* **Local ancestry inference -** Assigns each genome segment to likely ancestral origins. Helps with showing segment-by-segment ancestry rather than one overall percentage.
* **FineSTRUCTURE-like clustering -** Clusters individuals using haplotype-sharing patterns. Helps with detecting fine-scale subpopulation structure.
* **Haplotype sharing analysis -** Measures how much long-range haplotype material is shared between people or groups. Helps with identifying close population relationships and founder groups.
* **Rare-variant sharing analysis -** Compares uncommon variants that may be population-specific. Helps with strengthening fine-scale ancestry inference and recent population relatedness.



## **Direct historical population comparisons**

* **f-statistics (f3, f4) -** Formal tests of shared genetic drift and admixture. Helps with testing whether a population shares ancestry with another or is admixed from multiple sources.
* **D-statistics -** Tests asymmetry in allele sharing among populations. Helps determine whether one population is genetically closer to one reference than another.
* **qpAdm-like modeling -** Models a target population as a mixture of specified source populations. Helps with testing historical ancestry models.
* **qpGraph-like modeling -** Builds population graphs with splits and admixture edges. Helps reconstruct more complex population histories.
* **Treemix-like analysis -** Tree-based modelling with possible migration events. Helps visualise branching and gene flow among populations.
* **Direct ancient-modern affinity analysis -** Measures genetic similarity or shared ancestry between modern individuals/populations and ancient DNA samples. Helps test whether modern people show affinity to historical populations.
* **Ancient ancestry proportion modelling -** Estimates how much ancestry in a modern population can be explained by ancient source groups. Helps connect present-day populations to historically earlier populations.
* **Temporal population continuity analysis -** Tests whether genetic data are consistent with continuity between populations from different time periods, rather than replacement or major admixture. Helps assess whether a modern group plausibly descends from a historical one.



## **Understanding historical demographic background**

These look at how groups formed, mixed, expanded or remained isolated.

* **Runs of homozygosity (ROH) analysis -** Detects long stretches where both chromosome copies are identical. Helps with suggesting endogamy, bottlenecks, founder effects or recent relatedness within populations.
* **Endogamy analysis -** Uses patterns such as excess relatedness, homozygosity, and haplotype sharing to test for repeated within-group marriage. Helps explain why some populations are genetically distinctive.
* **Founder-effect analysis -** Uses allele frequencies, haplotypes, and relatedness patterns to detect descent from a small founding group. Helps identify historically isolated or bottlenecked populations.
* **Effective population size inference -** Estimates historical breeding population size from genetic data. Helps reconstruct demographic history of ancestral populations.
* **Bottleneck analysis -** Uses changes in diversity, homozygosity, and demographic modeling to detect past sharp reductions in population size. Helps explain drift and present-day distinctiveness.
* **Migration/gene-flow analysis -** Estimates movement of genes between populations. Helps determine how populations mixed over time.
* **Coalescent modelling -** Statistical modelling of genealogical history backward through time. Used to infer demographic and ancestral scenarios.



## **Matching the method to the question**

These approaches are not interchangeable. A method that establishes parentage does not answer the same question as one estimating ancient admixture. Population clustering, direct lineage, demographic history and administrative membership assessment involve different analytical tasks. The proposed verification system would therefore need to determine which methods are relevant to each kind of evidence or dispute.
