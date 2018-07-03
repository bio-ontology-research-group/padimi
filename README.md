# Ontology based mined Pathogen-Disease associations

textmined.nmpi-0.2_cnt-10_InfDis.txt contains all the pathogen-disease pairs extracted from literature. Our association extraction is based on sentence level co-occurrence of pathogen and disease and applying a filter for NMPI>=0.2 and number of co-occurrences>=10

The data format of this file is as follows:

NCBI TaxID||Disease_Ontology ID	Pathogen_name||Disease_name	#co-occurrences	#articles_containing_co-occureences	PMC_IDs	NPMI_value  sample_sentences

pairsFromExpansion.txt contains all the pairs expanded by using the literature extranct based on the Disease ontology. Briefly, the annotations of a given class is propaged to its all superclasses based on the ontology.

The data format of this file is as follows:

NCBI TaxID||Disease_Ontology ID
