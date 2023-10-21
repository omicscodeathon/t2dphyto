# Investigating the Molecular Connections between Natural Phytochemicals and Type II Diabetes


## Abstract
This study explores the potential of natural phytochemicals from various plants in treating Type II Diabetes (T2D). Using advanced computational techniques, we analyze their interactions with key receptors involved in T2D pathophysiology. Promising compounds, including kaempferol, ellagic acid, and 3-O-methyl ellagic acid, exhibit high binding affinities, indicating their potential as drug candidates. Their pharmacokinetic properties further support their suitability for T2D therapy. These findings provide a promising avenue for future research and development in T2D treatment.
In this study, we investigate potential molecular associations between natural phytochemicals and specific receptors linked to T2D. Employing advanced computational techniques, we systematically analyze the interaction of phytochemical compounds obtained from distinct botanical sources, including Momordica charantia L., Trigonella foenum-graecum L., Moringa oleifera, Psidium guajava, Allium cepa, Glycyrrhiza glabra, Gymnema sylvestre, Lagerstroemia speciosa, Salvia officinalis, and Urtica dioica, with receptors intricately implicated in T2D pathophysiology. This study elucidates the binding mechanisms and affinity patterns of these identified phytochemicals with pivotal receptors -alpha-glucosidase, alpha-amylase, and CAPN10-integral to insulin signaling and glucose homeostasis. The ADMET analysis additionally disclosed hydrophobic interactions, hydrogen bond acceptors, and hydrogen bond donors, confirming adherence to the Lipinski Rule of five.
These findings present a promising avenue for further research and development, offering tangible solutions in the fight against T2D.


#### Keywords: *Type 2 Diabetes, Molecular Modeling, Binding site, Phytochemicals, Virtual Screening*

## Objective:
The objective of this project is to investigate the molecular connections between various natural phytochemicals derived from different plants and type 2 diabetes using bioinformatics tools and methods. The project aims to identify potential mechanisms of action and therapeutic targets for the phytochemicals in the context of type 2 diabetes.

## Methods
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/workflow/Flowchart.jpg?raw=true)

Figure 1. Workflow

###  Results
1. Target Identification and Validation:

The biological targets were identified from the Pubmed database through a literature search (https://pubmed.ncbi.nlm.nih.gov/). The protein and gene sequence of the targets were retrieved from Uniprot (https://www.uniprot.org/) (Consortium, 2023) and Genbank (https://www.ncbi.nlm.nih.gov/genbank/) (Agarwal & Gupta, 2016) respectively. The physical and chemical properties of selected proteins were then accessed using the Protparam tool of the ExPASy website (https://web.expasy.org/protparam/) (Consortium, 2023). The 3-dimensional structure of  the CAPN10 protein was retrieved from the AlfaFold database of the EMBL_EBI server (https://alphafold.ebi.ac.uk/)(Sayers et al., 2020). The secondary structure analysis of caplain protein was generated using the PredictProtein tool (https://predictprotein.org/) (Gasteiger et al., 2003). The 3D models of proteins were validated by using the PDBsum database (http://www.ebi.ac.uk/thornton-srv/databases/pdbsum/) (Jumper et al., 2021). The other two biological receptors were identified by using the PDB (https://www.rcsb.org/) database with PBD IDs 5NN8 and 6OCN (Yachdav et al., 2014).

![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/capn10.png)

### 2. Binding site Prediction:
The binding site of protein was predicted using PrankWeb, a web server for ligand binding site prediction and visualization (https://prankweb.cz/) (Laskowski et al., 2018) and Computed Atlas of Surface Topography  (CastP, http://sts.bioe.uic.edu/castp/), a computational tool employed for the identification, quantification, and examination of cavities and vacant regions within three-dimensional protein architectures (Berman et al., 2000). The approach of employing both tools for the same task is underpinned by the principle of seeking consensus through the synthesis of predictions generated by both PrankWeb and CastP. By amalgamating the outcomes of these tools, we aimed to enhance the precision and reliability of the binding site prediction, thereby facilitating robust downstream analytical investigations.

![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/5td4_POCKET1_LIGANDS_prankweb.png)

![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/1smd_pocket_castp.png)
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/5td4_POCKET1_LIGANDS_prankweb.png)

### 3.  Pathway Analysis:
The pathway analysis was conducted using the following databases https://www.genome.jp/entry/K08579, https://www.genome.jp/entry/3.2.1.1, and https://www.genome.jp/entry/3.2.1.20 to verify CAPN10, α-amylase and α-glycosidase as biological targets implicated in Type II diabetes pathogenesis as well as identify pathways associated with our biological targets.
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/alpha%20glucosisase%20pathway.png)
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/amylase%20%20pathway.png)

### 4. Phytochemical Retrieval:
The phytochemicals were retrieved from IMPPAT (Indian Medicinal Plants, Phytochemistry And Therapeutics ) (https://cb.imsc.res.in/imppat/) (Jendele et al., 2019). The plants from which the phytochemicals were retrieved were *Momordica charantia L., Trigonella foenum-graecum L, Moringa oleifera Lam, Psidium guajava, Allium cepa, glycyrrhiza glabra, Gymnema sylvestre, Lagerstroemia speciosa, salvia officinalis, Urtica dioica*. About 17 Phytochemicals were retrieved from *Allium cepa*. Following that, 50 phytochemicals were taken from *Glycyrrhiza glabra*.

![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/glycerrhiza.png)
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/chemical_piechart.png)
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/moringa.png)

### 5. Compound Library Construction and Structure Elucidation:
The compound library was constructed based on retrieved phytochemicals.  The ligand structures were drawn and modified by using Chemsketch Software (https://www.acdlabs.com/resources/free-chemistry-software-apps/chemsketch-freeware/) (supplementary file 1). Exploration of quantum or classical model potential energy surfaces with single point, geometry optimization, or transition state search calculations of ligands was done by using Chebi tools, PDBsum (http://www.ebi.ac.uk/thornton-srv/databases/pdbsum/) (Jumper et al., 2021). The Compound library of approximately 458 phytochemicals was created using these tools and softwares.

### 6. Virtual Screening and Drug Likeness:
The screening of phytochemicals was conducted utilizing FAF-Drugs4, a virtual screening server accessible at https://mobyle.rpbs.univ-paris-diderot.fr/cgi-bin/portal.py#forms::FAF-Drugs4.  FAF-Drugs4 (Binkowski et al., 2003) represents an advanced approach amalgamating machine learning and molecular docking methodologies to forecast the Absorption, Distribution, Metabolism, and Excretion (ADME) attributes of candidate compounds.

### 7. Molecular docking analysis
The molecular docking analysis was performed using Autodock vina 1.2.5 (Trott & Olson, 2009). The 3D structures of 20 phytochemical compounds were retrieved from the PubChem database and it was saved as .pdbqt format using OpenBabel 2.4.1 package (O’Boyle et al., 2011). The crystal structure of α-amylase (6OCN), α-glucosidase (5NN8), and CAPN10 were downloaded from the PDB database and Alpha Fold platform. The grid map was generated using AutoGrid with a grid size of 80 × 80 × 80 with a grid spacing of 0.375 Å. The x, y, and z centers were used: 10.947, 84.307, and 151.746 respectively. The output file (.log) was obtained from the calculations and it was analyzed using the Discovery studio analyzer (Biovia, 2017).


### 8. Results:
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/complex%202.png)
![image](output/complex3.png)
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/output/docking.png)

### Conclusion:
This study presents compelling evidence supporting the potential of kaemferol, ellagic acid, and 3-O-methylellagic acid, extracted from Allium cepa and Lagerstromia speciosa, as promising drug candidates for Type II Diabetes (T2D) treatment. The demonstrated high binding affinities, particularly Kaemferol with Alpha amylase (-8.5), Ellagic acid with Alpha Glycosidase (-8.6), and 3-O-Methylellagic acid with CAPN10 (-7.7), underline their precise interactions with critical enzymes involved in T2D progression. Additionally, their favorable pharmacokinetic profiles enhance their potential for safe and effective clinical application in T2D management. These findings provide a focused and actionable foundation for further research and development in the pursuit of improved T2D therapeutics.


 ## Team Members
### 1. Shivani Pawar

### 2. Nigel Dolling

### 3. Musa Muhammad Shamsuddeen

### 4. Raphael Abban

### 5. Sivanandam Magudeeswaran
