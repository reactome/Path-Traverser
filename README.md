# Path-Traverser

## Pathway_StartEnd_Analysis.ipynb

This Jupyter notebook contain python scripts that
1. builds a reactions network based on curated and predicted reactions connections (more details on this is available in the reactome/connectivity-analyzer repository)
2. identifies start and end reactions based on graph properties
    1. start reactions are considered to have indegree=0 and outdegree>0
    2. end reactions are considered to have indegree>0 and outdegree=0
3. calculates shortest paths between start and end reactions
4. allows users to plot shortest paths between start and end reactions in a desired pathway
    1. with only manually curated reaction connections
    2. with manually curated and predicted reaction connections

## Pathway_StartEnd_Drug_Analysis.ipynb

This Jupyter notebook contains python scripts that
1. builds a reactions network based on curated and predicted reactions connections (more details on this is available in the reactome/connectivity-analyzer repository)
2. identifies start and end reactions based on graph properties
    1. start reactions are considered to have indegree=0 and outdegree>0
    2. end reactions are considered to have indegree>0 and outdegree=0
5. calculates shortest paths between start and end reactions
6. identifies drug-related reactions in Reactome
7. determines the shortest paths that involve these drug reactions
8. generates profiles of paths within a pathway that are affected by the introduction of a drug
