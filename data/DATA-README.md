# Summary of data input files

- `dpaint20_cmods.csv` includes compound id's, SMILES strings, and Chemformer embeddings for c-mods identified in the d.paint 20 assay.
- `cdcode_cmods.csv` includes compound id's, SMILES strings, and Chemformer embeddings for c-mods from CD-CODE. Also includes other information available from CD-CODE, such as pubchem ids for the relevant publication, chembl id's for each compound, and annotated molecular and targets.
- `dpaint20_cmpds_and_cmods.xlsx` includes compound id's for all compounds screened in the d.paint 20 assay. Also includes a sheet specifying the condensate targets of all d.paint c-mods that modulated just a single condensate.
- `updated_fda.csv` includes compound id's and SMILES strings for the library of drug-like compounds of which a major subset are the compounds screened in the d.paint 20 assay.
- `updated_fda_kinase_target_annotation.xlsx` includes  annotations for each compound of whether they inhibit a kinase or not.
