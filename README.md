# Environmental microbes
Metagenomic pipeline to scan waste water metagenomes for the known and unknown microbes and used in the following manuscript:

Anna J. Székely, Dhananjay Mukhedkar, Joakim Dillner, Ville N. Pimenoff. Integrated biological and chemical wastewater surveillance across Sweden reveals highly local dynamics of viral, bacteria and chemicals compositions (preprint)

Short description
The pipeline prepares quality-filtered using Trimmomatic or BBmap, and including the removal of duplicate reads. The taxonomic classification is performed using a Kmer matching algorithm and a K-mer matrix from the fully curated archaea, bacteria, virus and eukaryotic pathogen genomes reference genome database (v.2025), including the NCBI Viral Genome resource (https://ncbiinsights.ncbi.nlm.nih.gov/2023/1 0/19/changes-virus-data-resources-ncbi/, accessed on 1 January 2025) and the Eukaryotic Pathogen Genome Database (http://www.eupathdb.org/, accessed on 1 January 2025) as well as invertebrate, vertebrate, plant and mammalian genomes.

