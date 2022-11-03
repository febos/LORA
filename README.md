# LORA

A dataset of long-range RNA 3D modules

## Reference

[D.R. Bohdan, V.V. Voronina, J.M. Bujnicki, E.F. Baulin (2022) A comprehensive survey of long-range tertiary interactions and motifs in non-coding RNA structures. bioRxiv. DOI: 10.1101/2022.11.01.514747](https://doi.org/10.1101/2022.11.01.514747)

## Check out our [ARTEM tool](https://github.com/david-bogdan-r/ARTEM)

## Content 

### data

The coordinate files from PDB (Berman et al. 2000) and their annotations of the RNA interactions used in this work.

- **cif_files_part1.zip** & **cif_files_part2.zip** - Coordinate files in mmCIF format
- **pdb_files.zip** - Coordinate files in PDB format
- **clarna.zip** - ClaRNA annotations (Waleń et al. 2014)
- **dssr.zip** - DSSR annotations (Lu et al. 2015)
- **fr3d.zip** - FR3D annotations (Sarver et al. 2008)
- **mc-annotate.zip** - MC-Annotate annotations (Gendron et al. 2001)
- **rnaview.zip** - RNAView annotations (Yang et al. 2003)

### Table S1

The table of 17,272 long-range nucleotide doublets. For each doublet, the annotations of interactions and motif types are provided. Each doublet is assigned to a LORA module.

### modules

The dataset of 1,264 long-range RNA 3D modules (LORA modules). Each module is identified with its PDB entry and an ordinal number, e.g. *2z75_3*. All LORA modules are present in both mmCIF and PDB formats.

### motifs

The data on the long-range motif instances and motifs derived from the LORA modules. Motif instances are named using their source LORA module and an ordinal number, e.g. *2z75_1_259*. Motifs are named with the number of instances, motif size in residues, motif uniqueness, and the representative instance id, e.g. *118_9_0.99_6th6_56_1963*.

- **motifs_part1.zip** & **motifs_part2.zip** - the tables listing the residues of all the derived 1,156,112 motif instances.
- **clustering_round1** - intermediate results of step 1 of the custom clustering procedure. clst_N.txt files list a thousand intermediate clusters of size N. repr_N folders contain the cluster representatives in mmCIF format.
- **clustering_round2** - the derived 2,733 long-range RNA tertiary motifs. All the motifs are present in both mmCIF and PDB formats.
- **top_frequent** - archives with the data on the top 424 motifs having at least 100 instances. Each archive contains all the instances belonging to the given motif (mmCIF + PDB) along with a tsv table listing RMSD and the nucleotide matchings between the instances.
