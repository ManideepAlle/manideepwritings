# Molecular docking of Histone deacetylases subtypes.
## Authors (@slack) :
Alle Manideep(@Manideep)
Chamss Daghsni (@ChamssDaghsni)
##Introduction

Histone deacetylases (HDACs) are enzymes involved in chromatin remodeling through the removal of acetyl groups from histones, leading to condensed chromatin and reduced gene transcription. Their role in silencing tumor suppressor genes has made them important drug targets for cancer therapy. Dysregulation or overexpression of HDACs is frequently observed in various cancers, promoting uncontrolled cell growth and tumor progression.

HDACs are divided into four classes, with class I, II, and IV enzymes being zinc-dependent. Among them, HDAC11, the sole member of class IV, is increasingly recognized for its involvement in cancer and other diseases. HDAC11’s unique biological functions make it a particularly attractive target for selective inhibition, which could lead to more precise cancer treatments with fewer off-target effects.

Several selective HDAC11 inhibitors, such as FT895 and SIS17, have been developed and shown efficacy in reducing cancer cell viability, particularly in non-small cell lung cancer. Although the absence of a crystal structure for HDAC11 complicates drug design, AI-driven approaches like AlphaFold have enabled the prediction of HDAC11’s structure. These models have been used successfully in virtual screening and structure-based design, making HDAC11 a promising target for future anticancer therapies.

## Methodology
## proteins preparation
The proteins HDAC1,HDAC2,HDAC3,HDAC4,HDAC5,HDAC6,HDAC7,HDAC8,HDAC9,HDAC10 structures downloded from PDB data base and the HDAC11 protein structure modeled using the Alphafold. Cleaning of the protein structure was done using PyMOL by removing water molecules together with bound ligands/hetero atoms. Hydrogens were thereafter added to the structure.
Changes were finally added to the protein with the help of tools available in PyMOL to ensure proper molecular interactions.

## ligands library preparation
The 50 phytochemical of turmeric and 11 inhibitors of 11 HDAC's one for each according to the literature, Total of 61 lignads are downloaded from Pubchem in SDF format. The energy minimization of all 61 ligands was done using PyRx and after that the structures of protein and ligand were converted to the pdbqt format for docking.

## Molecular Docking
The docking were conducted with the aid of a grid box laid over the active site, creating multiple binding modes for each ligand in the PyRx.To enhance reliability, docking simulations were performed in triplicate for each protein-ligand pair, with binding affinities (docking scores) calculated. The mean and standard deviation of the results were then computed to identify the ligands that demonstrated the strongest and most consistent binding affinities for each HDAC subtype.

## Results


[results table.md.xlsx](https://github.com/user-attachments/files/17344320/results.table.md.xlsx)




 
