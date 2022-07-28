### Title: 
***Mapping MeSH (ICD codes) to molecular mechanism through protein-protein co-occurance graph***

### Detail:

<img src="plots/pmed.png" alt="drawing" width="400"/>

Fig: Sigdel et. al., Understanding the Molecular Interface
of Cardiovascular Diseases and COVID-19:
A Data Science Approach, Advanced Technologies in Cardiovascular Bioengineering


One of the central idea in personalized medicine is to understanding the disease and symptoms in terms of molecular phenotypes. Bridging molecular phenotypes to disease signs and symptoms is a challenging task. The bigest question is building the personal interactome through the interface of personal omics and past history of medical records (e.g., EHR, EMR). In this project, our attempt will be to create a mapping of Medical Subjet Heading (MeSH/ICD) to relevant protein-protein co-occurance graph. Since MeSH terms are organized in hierarchical tree structure, we are only considering the leaf nodes of the cardiovascular tree.  With protein-protein co-occurance graph, one can extend it to relevant genes, metabolites and molecular pathways. 

### Data Sources

1. PubMed
2. MeSH Trees

### Project Walkthrough

1. Prepare Cardiovascular Documents from PubMed
2. Get MeSH terms (MeSH tree 20222) from NLM library 
3. Build MeSH to PMID and PMID to MeSH mapping through caseOLAP platform
4. Build document to entity mapping (PMID to protein mapping) through caseOLAP platform
5. Create MeSH to entities mapping for leaf nodes of the CVD meSH tree.
6. Create protein-protein co-occurance graph by utilizing document to entity mapping
7. Integrate protein-protein co-ocurrance graph with MeSH, Pathways, Drugs, Metabolites information.
8. Load graph data in Neo4J platform for further exploration

### Educational Goal:
This project offers the opportunity of learning about disease terminologies (MeSH/ICD codes) as tree data structure. These data structure play key role in organizing documents in databases (e.g., MeSH in PubMed, ICD codes in EHR database). Implementing knowledggraph for targeted disese/symptoms to molecular mechanism is central construct of creating a interface of personl EHR data and scientific research.

### Scientific Goal:


### References: 



