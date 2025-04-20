# metabarcoding_antar

This repository contains data used for in "Biodiversity and Trophic Connections in Antarctica: A Multi-Compartment eDNA Metabarcoding Approach" by Gustavo F. de Carvalho-Souza, Antonio Tovar-Sánchez, Francisco Baldó and Enrique González-Ortegón.

Included are:

The metabarcoding_antar dataset. The database contains data derived from environmental DNA (eDNA) metabarcoding analysis. Each row represents an observation unit corresponding to an operational taxonomic unit (OTU) identified in a given sample. The variable OTU_ID refers to a unique genetic identifier assigned to each OTU. Taxonomic classification is provided across hierarchical ranks, from kingdom to species, allowing detailed taxonomic resolution when available. The sample column indicates the original name or identifier of the biological or environmental sample.

The value column contains the number of sequencing reads assigned to each OTU within a sample, which is used as a proxy for relative abundance. The type variable denotes the sampled compartment (e.g., faecal material, krill stomach contents, water), while site indicates the geographic location of sample collection. The primer column specifies the DNA marker used to amplify the target genetic region for each OTU (e.g., 12S, 16S, COI).

To facilitate ecological categorization, the group column classifies each OTU as either Metazoa or Non-Metazoa, while the subgroup variable provides further taxonomic refinement (e.g., Arthropoda, Diatoms).
