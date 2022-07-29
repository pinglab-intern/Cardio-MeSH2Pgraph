## Ping Lab Intern Project, Summar, 2022

### Title: 
***Mapping MeSH (ICD codes) to the molecular mechanism through the protein-protein co-occurrence graph -toward high precision medicine***

### Detail:

One of the central ideas in personalized medicine is to understand the disease and symptoms in terms of molecular phenotypes. Bridging molecular phenotypes to disease signs and symptoms is a challenging task. The biggest question is building the personal interactome through the interface of personal omics and the history of medical records (e.g., EHR, EMR). In this project, we will attempt to create a mapping of Medical Subject Heading (MeSH/ICD) to a relevant protein-protein co-occurrence graph. Since MeSH terms are organized in the hierarchical tree structure, we are only considering the leaf nodes of the cardiovascular tree. One can extend the protein-protein co-occurrence graph to relevant genes, metabolites, and molecular pathways. 

<img src="plots/pmed.png" alt="drawing" width="500"/>

Figure: Sigdel et al., Understanding the Molecular Interface of 
Cardiovascular Diseases and COVID-19:A Data Science Approach, 
Advanced Technologies in Cardiovascular Bioengineering, 2022


### Data Sources

1. [PubMed API](https://www.ncbi.nlm.nih.gov/home/develop/api/)
2. [MeSH Trees](https://www.nlm.nih.gov/mesh/meshhome.html)

### Project Walkthrough

1. Prepare Cardiovascular Documents from PubMed
2. Get MeSH terms (MeSH tree 20222) from the NLM library 
3. Build MeSH to PMID and PMID to MeSH mapping through the caseOLAP platform
4. Build document to entity mapping (PMID to protein mapping) through the caseOLAP platform
5. Create MeSH to entities mapping for leaf nodes of the CVD meSH tree.
6. Create a protein-protein co-occurrence graph by utilizing document to entity mapping
7. Integrate protein-protein co-occurrence graph with MeSH, Pathways, Drugs, and Metabolites information.
8. Load graph data in the Neo4J platform for further exploration

### Educational Goal:
This project offers the opportunity of learning about disease terminologies (MeSH/ICD codes) as the tree data structure. These data structures play a key role in organizing documents in databases (e.g., MeSH in PubMed, ICD codes in EHR database). Implementing text-mining and knowledge graphs for targeted diseases/symptoms to molecular mechanisms is a central construct of creating an interface of personal EHR data and scientific research. The take-home skills in this project are text-mining, data engineering with graph data, and AI algorithms.

### Scientific Goal:
Implementation of text-mining for building mapping of MeSH (ICD codes) to the molecular mechanism through protein-protein co-occurrence graph provides new insight toward high precision medicine. In the case of medical informatics, this approach will help build automated cohort selection and patient classification. It will help create a personalized interface of clinical and biomedical information.

### References: 
1. [International Classification of Diseases (ICD)](https://www.who.int/standards/classifications/classification-of-diseases)
2. [Reactome](https://reactome.org)
3. [Drug Bank](https://www.drugbank.com)
4. [HMDB](https://hmdb.ca)
5. [Graph Academy](https://neo4j.com/graphacademy/)
6. [Graph Data Science Library -GDS](https://neo4j.com/docs/graph-data-science/current/algorithms/)
