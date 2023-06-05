# Protein Data Set Readme

## About Dataset

This dataset contains protein data retrieved from the Research Collaboratory for Structural Bioinformatics (RCSB) Protein Data Bank (PDB). The PDB archive serves as a repository for atomic coordinates and other relevant information regarding proteins and other biological macromolecules. Structural biologists employ techniques such as X-ray crystallography, NMR spectroscopy, and cryo-electron microscopy to determine the spatial arrangement of atoms within molecules. This information is then deposited, annotated, and made publicly available through the archive by the wwPDB.

The PDB archive is constantly expanding, reflecting ongoing research conducted in laboratories worldwide. It provides an extensive collection of structures for various proteins and nucleic acids involved in crucial life processes. Users can access structures of ribosomes, oncogenes, drug targets, and even whole viruses. However, due to the diverse range of structures stored in the PDB, finding specific information can be challenging. The archive contains multiple structures for a single molecule, partial structures, and modified or inactivated forms of native structures.

## Content

This dataset consists of two data files, organized based on the "structureId" of the protein:

1. `pdb_data_no_dups.csv`: This file contains protein metadata, including details about protein classification, extraction methods, and other relevant information.

2. `data_seq.csv`: This file contains over 400,000 protein structure sequences.

## Acknowledgements

The original dataset was downloaded from the [RCSB Protein Data Bank (PDB)](http://www.rcsb.org/pdb/).

## Inspiration

The Protein Data Bank has been instrumental in advancing research within the life science community. It has facilitated the study of various diseases and has contributed to the development of new drugs and solutions aimed at improving human survival.
