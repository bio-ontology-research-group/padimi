# Ontology based mined Pathogen-Disease associations

expanded.InfDis.Pairs.pathogen-disease+NPMI.txt contains all the pathogen-disease pairs extracted from literature. Our association extraction is based on sentence level co-occurrence of pathogen and disease and applying a filter for NMPI>=0.2 and number of co-occurrences>=10

The data format of this file is as follows:

NCBI_TaxonomyID##Disease_Ontology_ID  #co-occurrences NPMI_value
