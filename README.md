# Molecular Connections between Various Natural Phytochemicals from different Plants and Type 2 Diabetes: A Bioinformatics Approach


## Abstract *(max 250 words)*

Type 2 diabetes (T2D) is a complex metabolic disorder characterized by insulin resistance and impaired glucose metabolism. Despite the availability of antidiabetic drugs, their limited efficacy necessitates the development of novel therapeutic approaches. This study explores potential molecular connections between natural phytochemicals and specific receptors associated with T2D. Utilizing advanced computational molecular modeling techniques, this research systematically analyzes the interaction dynamics of phytochemical compounds sourced from different segments of medicinal plants such as Momordica charantia L., Trigonella foenum-graecum L, Moringa oleifera Lam, aloe, Psidium guajava, Allium cepa, glycyrrhiza glabra, Gymnema sylvestre, Lagerstroemia speciosa, salvia officinalis, urtica dioica, with receptors intricately linked to T2D pathophysiology. By employing cutting-edge molecular modeling tools, this study aims to decipher the binding mechanisms and affinity patterns of these identified phytochemicals with key receptors responsible for insulin signaling, glucose homeostasis, and inflammation regulation.
The outcomes of this investigation hold the promise of unveiling deeper insights into the structural compatibility and potential mechanisms governing the interactions between diverse plant-derived compounds and their respective target receptors. Such insights may contribute to an enhanced understanding of the therapeutic implications of kaempferol and other phytochemicals in modulating pathways pertinent to Type 2 diabetes.
Furthermore, the proposed computational methodologies could facilitate the accelerated identification of promising natural compounds, potentially leading to the development of innovative antidiabetic medications. In summary, this study employs a comprehensive computational approach to elucidate the molecular associations between phytochemicals and receptors relevant to Type 2 diabetes. The findings may pave the way for novel therapeutic strategies in T2D management, harnessing the potential of phytochemicals derived from a variety of medicinal plants.

#### Keywords: *Type 2 Diabetes, Molecular Modeling, Binding site, Phytochemicals, Virtual Screening*

## Objective:
The objective of this project is to investigate the molecular connections between various natural phytochemicals derived from different plants and type 2 diabetes using bioinformatics tools and methods. The project aims to identify potential mechanisms of action and therapeutic targets for the phytochemicals in the context of type 2 diabetes.

## Methods
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/workflow/Flowchart.jpg?raw=true)
Figure 1. Workflow

### 1. Identification of Target and Validation:
The biological target was identified by using pubmed database (https://pubmed.ncbi.nlm.nih.gov/). The protein and gene sequence of target were retrieved from uniprot ( https://www.uniprot.org/ ) and genbank (https://www.ncbi.nlm.nih.gov/genbank/) respectively.
The physical and chemical properties of selected proteins were then accessed using protparam tool of ExPASy website (https://web.expasy.org/protparam/). The 3-Dimensional structure of  CAPN10 protein was retrieved from AlfaFold database of EMBL_EBI server (https://alphafold.ebi.ac.uk/). The secondary structure analysis of caplain protein was done by using PredictProtein tool (https://predictprotein.org/). The 3D model pf protein were validated by using PDBsum database (http://www.ebi.ac.uk/thornton-srv/databases/pdbsum/). The other 2 biological receptors were identified by using PDB (https://www.rcsb.org/) database.

### 2. Binding site Prediction:
The binding  site of protein was predicted using PrankWeb, a web server for ligand binding site prediction and visualization (https://prankweb.cz/) and Computed Atlas of Surface Topography  (CastP, http://sts.bioe.uic.edu/castp/), a computational tool employed for the identification, quantification, and examination of cavities and vacant regions within three-dimensional protein architectures. The approach of employing both tools for the same task is underpinned by the principle of seeking consensus through the synthesis of predictions generated by both PrankWeb and CastP. By amalgamating the outcomes of these tools, we aimed at enhancing the precision and reliability of the binding site prediction, thereby facilitating robust downstream analytical investigations.

### 3. Compound Library construction and Structure Elucidation :
The  phytochemicals were retrieved from IMPPAT  (Indian Medicinal Plants, Phytochemistry And Therapeutics ), (https://cb.imsc.res.in/imppat/). 
The plants from which phytochemicals were retrieved are Momordica charantia L., Trigonella foenum-graecum L, Moringa oleifera Lam, aloe, Psidium guajava, Allium cepa, Glycyrrhiza glabra, Gymnema sylvestre, Lagerstroemia speciosa, Salvia officinalis, Urtica dioica. The ligand structures were drawn and modified by using Chemsketch Software (https://www.acdlabs.com/resources/free-chemistry-software-apps/chemsketch-freeware/).  Exploration of quantum or classical model potential energy surfaces with single point, geometry optimization, or transition state search calculations of ligands was done by using Chebi tools, PDBsum (http://www.ebi.ac.uk/thornton-srv/databases/pdbsum/).

### 4. Virtual Screening and Drug Likeness : 
Twenty (20) phytochemicals were retrieved from the plant Urtica dioica. Out of them 7 phytochemicals were selected. The various physicochemical properties on which basis the compounds were screened. The properties comprise hydrogen bond acceptors, hydrogen bond donors, logP and molecular weight.
A total of 34 phytochemicals were retrieved from the plant Trigonella foenum-graecum out of which 29 phytochemicals were accepted. The various physicochemical properties on which basis the compounds were screened. The properties comprise hydrogen bond acceptors, hydrogen bond donors, logP and molecular weight.
A total of 37 phytochemicals were retrieved from the plant momordica charantia. The results shows the various physicochemical properties on which basis the compounds were screened. The properties comprise hydrogen bond acceptors, hydrogen bond donors, logP and molecular weight.

### 5. Pathway Analysis : 
To determine if these receptors (Biological targets) are relevant to type 2 diabetes and associated complications, pathway analysis was done.

![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/alpha_glucosidase_pathway.png)

Figure 2. Alpha Glucosidase Pathway


      
![image](https://github.com/omicscodeathon/t2dphyto/blob/main/figures/amylase_pathway.png?raw=true)

Figure 3. Amylase Pathway



### Data Integration and Interpretation:
Integrate findings from docking, screening, network, and pathway analysis.
Interpret results considering known diabetes mechanisms and literature.
Generate testable hypotheses regarding phytochemical therapeutic potential.



## Expected Outcomes:
1. Identification of phytochemicals with potential against type 2 diabetes.

2. Prediction of phytochemical-protein interactions.

3. Insight into enriched pathways associated with target proteins.

4. Understanding of connections between phytochemicals and diabetes, aiding therapeutic development.


