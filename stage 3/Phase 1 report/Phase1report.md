# Virtual screening by Molecular docking of anti-cancer activity of turmeric phytochemicals compounds that target S100A16 on patients with lung cancer
## Authors (@slack) :
## Introduction:
Lung cancer remains a leading cause of cancer-related mortality worldwide, with limited treatment options and poor outcomes, especially in advanced stages. Among the molecular targets of interest for potential therapeutic interventions is S100A16, a calcium-binding protein involved in various cellular processes. Recent studies have shown that S100A16 expression is associated with poor prognosis in lung cancer patients, particularly in lung adenocarcinoma (LUAD). Survival analysis based on S100A16 expression revealed a significant correlation, with a cutoff at 118.4 FPKM (fragments per kilobase of transcript per million), separating patients into two groups: those with high S100A16 expression, who exhibit a 5-year survival rate of 43%, and those with low expression, with a 46% survival rate (p-value: 3.14e-5). This significant association suggests that targeting S100A16 may offer therapeutic potential specifically in LUAD.

S100A16 also plays roles beyond tumorigenesis, including enhancing adipogenesis and reducing insulin-stimulated glucose uptake, implicating its broader physiological relevance. Immunohistochemical staining using the HPA045841 antibody further highlights its differential expression in lung cancer samples, indicating that it could serve as a biomarker for specific subtypes of lung cancer.

In the search for novel therapeutic approaches, turmeric (Curcuma longa) and its bioactive compounds, including curcumin, have gained attention due to their anti-inflammatory, antioxidant, and anti-cancer properties. This study aims to explore the potential of turmeric-derived compounds to target S100A16 in LUAD using virtual screening and molecular docking techniques. By identifying compounds with a strong binding affinity to S100A16, this research may contribute to the development of novel, plant-based therapies for lung cancer, providing a natural, complementary strategy alongside existing treatments.

## Phytochemical libraries:
A library of 50 phytochemicals from turmeric was curated. Complete details of these phytochemicals were documented. This library would be useful in the next step of molecular docking by providing a set of phytochemicals with their structures for the interaction analysis.

## Protein preparation:
A protein structure with PDB ID 3NXA, which corresponds to S100 calcium binding protein A16(S100A16), was selected as the target for docking analysis.

Cleaning of the protein structure was done using PyMOL by removing water molecules together with bound ligands/hetero atoms. Hydrogens were thereafter added to the structure.

Charges were finally added to the protein with the help of tools available in PyMOL to ensure proper molecular interactions.
![image_of_protein_after_modification](https://github.com/user-attachments/assets/50ae75c8-a04b-49d7-929e-25941b18510f) Fig 1:Visualization of prepared protein

## Molecular Docking of Turmeric Compounds against S100A16
 
