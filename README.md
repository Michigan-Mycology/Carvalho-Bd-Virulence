# Carvalho-Bd-Virulence
Data sets and code for Carvalho et al. Amphibian Hymenochirus boettgeri as an experimental model for infection studies with the chytrid fungus Batrachochytrium dendrobatidis

[![DOI](https://zenodo.org/badge/703987640.svg)](https://zenodo.org/badge/latestdoi/703987640)

This readme file was generated on 2023-06-01 by Tamilie Carvalho

GENERAL INFORMATION

Title of Dataset: Amphibian Hymenochirus boettgeri as an experimental model for infection studies with the chytrid fungus Batrachochytrium dendrobatidis.

Author Information
Name: Tamilie Carvalho
ORCID: https://orcid.org/0000-0001-7300-2777
Institution: University of Michigan
Address: 2220 Biological Science Building, 1105 North University, Ann Arbor, MI 48109-1085, USA.
Email: tamiliec@gmail.com; tamilie@umich.edu


Date of data collection: 2022-03-01 to 2022-09-01 

Geographic location of data collection: Ann Arbor, USA. 

Information about funding sources that supported the collection of the data: This work was supported by the Gordon and Betty Moore Foundation Award #9337 (10.37807/GBMF9337). TYJ is a Fellow in the CIFAR program Fungal Kingdom: Threats and Opportunities. The work was partially supported by a catalyst grant from CIFAR and CIFAR fellowship funds. 

Recommended citation for this dataset: Carvalho, T; Si, C.; Clemons, A.R; Faust, E; James, T.Y. 2023. Amphibian Hymenochirus boettgeri as an experimental model for infection studies with the chytrid fungus Batrachochytrium dendrobatidis.


DATA & FILE OVERVIEW

File List: 
1. Bd_dosage_response.csv
2. Modelgeneralizability.csv
3. Validation.csv
4. Statistical_analyses.Rmd
   

Relationship between files: 
Use files number 1, 2 and 3 to run R code number 4.


DATA-SPECIFIC INFORMATION FOR: Bd_dosage_response.csv

Number of variables: 3

Number of rows: 36

Variable List:
1. Treatment: Treatments reflect the combination of genotypes (JEL423 or CLFT073) and Bd dose (HD - high dose and LD - low dose), and a control group.

2. Mortality_day: Values reflect the number of days until death after exposure to the pathogen.

3. Censor: 1 when the frog died, and 0 when it survived until the end of the experiment.


DATA-SPECIFIC INFORMATION FOR: Modelgeneralizability.csv

Number of variables: 4

Number of rows: 70

Variable List:
1. Censor: 1 when the frog died, and 0 when it survived until the end of the experiment. 

2. Mortality_day: Values reflect the number of days until death after exposure to the pathogen.

3. Genotype: Genotype name used in the exposure treatment and a Control group.

4. Lineage: Name of the lineages to which the genotypes used in the exposure experiment belong. Control (No lineages/genotypes used).



DATA-SPECIFIC INFORMATION FOR: Validation.csv

Number of variables: 6

Number of rows: 40

Variable List: 
1. ID: Frog identification number.

2. Bd_Load: Bd pathogen load.

3. Genotype_experiment: Combinations of genotypes (CLFLT150 or CLFT039) and experiments (MG - model generalizability or V - validation) of each treatment and control groups.

4. Censor: 1 when the frog died, and 0 when it survived until the end of the experiment. 

5. Mortality_day: Values reflect the number of days until death after exposure to the pathogen.

6. Lineage: Name of the lineages to which the genotypes used in the exposure experiment belong. Control (No lineages/genotypes used).
