# LORA

A dataset of long-range RNA 3D modules

## Reference

[D.R. Bohdan, V.V. Voronina, J.M. Bujnicki, E.F. Baulin (2023) A comprehensive survey of long-range tertiary interactions and motifs in non-coding RNA structures. Nucleic Acids Research. gkad605. DOI: 10.1093/nar/gkad605](https://doi.org/10.1093/nar/gkad605)

## Check out [our other developments](https://github.com/febos/wiki)

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

The non-redundant list of 97 RNA chains used in this work.

### Table S2

The table of 17,272 long-range nucleotide doublets. For each doublet, the annotations of interactions and motif types are provided. Each doublet is assigned to a LORA module.

### Table S3

The table of 180 long-range doublets annotated with different Leontis-Westhof base pair types by different tools.

### Table S4

The table of 35 D-loop/T-loop-like motifs.

### Table S5

The table of 45 long-range tertiary motifs.

### Table S6

The table of 3880 long-range tertiary motif matches in the LORA modules.

### Table S7

The table of 515 long-range doublets matching the cSS base pair motif (motif 1).

### Table S8

The table of 1,264 LORA modules annotated with their descriptive types and involved interactions andd motifs. 

### Table S9

The table of 17 RINs and 24 LORA modules from the intersection in PDB entries between LORA and CaRNAval database (Reinharz et al. 2018).

### modules

The dataset of 1,264 long-range RNA 3D modules (LORA modules). Each module is identified with its PDB entry and an ordinal number, e.g. *2z75_3*. All LORA modules are present in both mmCIF and PDB formats.

### motifs

The data on the long-range motif instances and motifs derived from the LORA modules. Motif instances are named using their source LORA module and an ordinal number, e.g. *2z75_1_259*. 

- **motifs.zip** - the table listing the residues of all the derived 489,999 motif instances.
- **clusters** - intermediate clusters of the motif instances from 2 to 20 residues in size. All cluster members are present in PDB format. Cluster centers are present in PDB and mmCIF formats.
- **library** - the derived 45 long-range RNA tertiary motifs. All the motifs are present in both mmCIF and PDB formats.
- **matches** - the derived 3880 long-range RNA tertiary motif matches in the LORA modules. All the motif matches are present in both mmCIF and PDB formats.
