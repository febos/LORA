
motif_size_N.zip - clusters of N-residue motifs.

What's inside:
-------------------------------------
clusters_table.tsv - table of clusters
Columns:
CLUSTER_SIZE - number of motifs within the cluster
MOTIFS_ID - names of the motifs
-------------------------------------
centroids - folder with cluster centroids in CIF and PDB formats
(all the files are named as CLUSTERSIZE_MOTIFID.cif or
CLUSTERSIZE_MOTIFID.pdb, where MOTIFID is the name of the 
centroid motif)
-------------------------------------
clusters - folders with all the motifs of the clusters in PDB format
(all the folders are named as CLUSTERSIZE_MOTIFID, 
where MOTIFID is the name of the centroid motif;
all the files are named as NNN_MOTIFID.pdb, where
NNN is MAXRESRMSD with respect to the centroid multiplied by 1000)
