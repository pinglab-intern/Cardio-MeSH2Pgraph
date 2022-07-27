### Title: 
***Mapping MeSH (ICD codes) to molecular mechanism through protein-protein co-occurance graph***

### Detail:

One of the central idea in personalized medicine is to understanding the disease in terms of molecular mechanism in personal interactome. The personal interactome could be built through personal omics and past history of medical records (e.g., EHR, EMR). In this project, our attempt will be to create a mapping of Medical Subjet Heading (MeSH) to relevant protein-protein co-occurance graph. Since MeSH terms are organized in hierarchical tree structure, we are only considering the leaf nodes of the cardiovascular tree.  With protein-protein co-occurance graph, one can extend it to relevant genes, metabolites and molecular pathways. 

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


### Scientific Goal:


### References: 



