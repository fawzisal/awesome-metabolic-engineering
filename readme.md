<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->
# Awesome Metabolic Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/fawzisal/awesome-metabolic-engineering/actions/workflows/lint.yaml/badge.svg)](https://github.com/fawzisal/awesome-metabolic-engineering/actions/workflows/lint.yaml)

<!-- subtitle -->

Packages, toolboxes, models

<!-- image -->

<!-- <a href=" target="_blank" rel="noopener noreferrer">
  <img src=" />
</a> -->

<!-- description -->

A collection of tools for constraint-based modelling (CBM), flux balance analysis (FBA), and related fields. Please feel free to [contribute](contributing.md)!



</div>

<!-- TOC -->

## Contents

- [Toolboxes](#toolboxes)
- [Model Repositories](#model-repositories)
<!--
- [Abbreviations](#abbreviations)
- [Follow](#follow)
 -->

<!-- CONTENT -->

## Tools & Toolboxes

# Simulation
- [Cobra](https://github.com/opencobra): the standard FBA tool
	+ [CobraToolbox](https://github.com/opencobra/CobraToolbox) - in MATLAB
	+ [CobraPy](https://github.com/opencobra/CobraPy) - in Python
- [LCSB-BioCore/COBREXA.jl](https://github.com/LCSB-BioCore/COBREXA.jl): Cobra for exa-scale metabolic models in Julia
- [Raven](https://github.com/SysBioChalmers/RAVEN): Reconstruction, Analysis and Visualization of Metabolic Networks
- [CellNetAnalyzer](https://www2.mpi-magdeburg.mpg.de/projects/cna/cna.html): A toolbox providing a graphical user interface and various computational methods and algorithms for exploring structural and functional properties of metabolic, signaling, and regulatory networks.
	+ [CellNetAnalyzer](https://www2.mpi-magdeburg.mpg.de/projects/cna/cna.html) - in MATLAB
	+ [CNApy](https://github.com/cnapy-org/CNApy) - in Python
- [reframed](https://github.com/cdanielmachado/reframed): metabolic modeling package
	+ [framed](https://github.com/cdanielmachado/framed) - the older version of package
- [PySCeS Constraint Based Modelling](https://github.com/SystemsBioinformatics/cbmpy): a new platform for constraint based modelling and analysis
- [BioSystemsUM/mewpy](https://github.com/BioSystemsUM/mewpy): Metabolic Engineering Workbench, under development, for strain design optimization
- [maxconway/fbar](https://github.com/maxconway/fbar): Flux Balance Analysis package with a tidy data approach. Models are expected as a flat table, and results can be simply appended to the table. This makes this package very suitable for useage in pipelines with pre- and post- processing of models and results.

<!--
## OLDER
- [MOST](https://github.com/dennisegen/MOST): in Java
- [IBRENA](https://www.eng.buffalo.edu/~neel/ibrena): in ?
- [sybil](https://cran.r-project.org/web/packages/sybil/index.html): in R
- [sybilccFBA](https://cran.r-project.org/web/packages/sybilccFBA/index.html): in R
- [sybilcycleFreeFlux](https://cran.r-project.org/web/packages/sybilcycleFreeFlux/index.html): in R
-->

# Web-based
- [KBase](https://www.kbase.us/): An integrated platform for web-based systems biology, including tools to build, manipulate and analyze metabolic models.
- [DD-DeCaF](https://caffeine.dd-decaf.eu/): Bioinformatics Services for Data-Driven Design of Cell Factories and Communities
	+ [tutorials](https://github.com/DD-DeCaF/tutorials) - on github

# Specialized
- `recon` [zhanglab/psamm](https://github.com/zhanglab/psamm): for the curation and analysis of metabolic models
- `design` [biosustain/cameo](https://github.com/biosustain/cameo): a high-level python library developed to aid the strain design process in metabolic engineering projects
- `recon` [cdanielmachado/carveme](https://github.com/cdanielmachado/carveme)
- `recon` [mauriceling/advancesyntoolkit](https://github.com/mauriceling/advancesyntoolkit)

## Model Respositories

- [BiGG Models](http://bigg.ucsd.edu/): >100 high-quality GEMs.
- [MetaNetX](https://www.metanetx.org/): Includes a repository of models from, for example, BiGG or the Model SEED, networks from BioCyc, and metabolic pathways from Reactome; all reconciled in a common namespace defined by MNXref.
- [ModelSEED](https://modelseed.org/): A tool to automatically generate a metabolic model give a genome.

## Microbial Communities
- [beatrizgj/FLYCOP](https://github.com/beatrizgj/FLYCOP): FLYCOP (FLexible sYnthetic Consortium OPtimization)
- [mgtools/PhyloMint](https://github.com/mgtools/PhyloMint): Pathway-based and phylogenetically adjusted quantification of competition and cooperation between microbial species
- [franciscozorrilla/metaGEM](https://github.com/franciscozorrilla/metaGEM): :gem: An easy-to-use workflow for generating context specific genome-scale metabolic models and predicting metabolic interactions within microbial communities directly from metagenomic data
- [borenstein-lab/CoMiDA](https://github.com/borenstein-lab/CoMiDA): The code and distributable for designing minimal microbial communities with specified metabolic functions.
- [yumyai/MetGEMs](https://github.com/yumyai/MetGEMs): Community Metabolic Network constructor
- [klamt-lab/CommModelPy](https://github.com/klamt-lab/CommModelPy): Create stoichiometric metabolic network models of single-species or multi-species communities
- [katebrich/Bacteria_community_interactions_analysis](https://github.com/katebrich/Bacteria_community_interactions_analysis): Mini-project on Genome-scale metabolic modelling. Created in EMBL Heidelberg.
- [SophiaSantos/Minimal_Medium_Community_Analysis](https://github.com/SophiaSantos/Minimal_Medium_Community_Analysis): Scripts of analysis of minimal medium composition on single organisms and communities of Inferring optimal minimal medium on genome-scale metabolic models using evolutionary algorithms. – Metabolic Pathway Analysis Conference, Riga, Latvia, 12-16 August, 2019.
- [eltanin4/cross_feeding](https://github.com/eltanin4/cross_feeding): Scripts and data files for "The chemical basis of metabolic cooperation in microbial communities"
- [cristalzucsd/SyntheticMicrobialCommunities](https://github.com/cristalzucsd/SyntheticMicrobialCommunities): Microbial communities were rationally assembled as bioproduction platforms. The metabolic models of a sucrose-secreting Synechococcus elongatus, two strains of Escherichia coli, Yarrowia lipolytica, and Bacillus subtilis were paired in phototroph-heterotroph combinations. 
- [QTB-HHU/daphne_ecoli-diauxie](https://github.com/QTB-HHU/daphne_ecoli-diauxie): Emergent sub-population behavior uncovered with a community dynamic metabolic model of Escherichia coli diauxic growth
- [euba/BacArena](https://github.com/euba/BacArena): agent based modelling
- [micom-dev/micom](https://github.com/micom-dev/micom): Python package to study microbial communities using metabolic modeling.
- [jjborrelli/MetabolicMicrobe](https://github.com/jjborrelli/MetabolicMicrobe): Functions associated with metabolic modeling of microbial communities
- [cdanielmachado/designmc](https://github.com/cdanielmachado/designmc): Designing microbial communities
- [cdanielmachado/smetana](https://github.com/cdanielmachado/smetana): SMETANA: a tool to analyse interactions in microbial communities
- [peishunSysbio/cvdGEMs](https://github.com/peishunSysbio/cvdGEMs): Genome-scale metabolic modeling of gut microbiota associated with CVD
- [biobakery/melonnpan](https://github.com/biobakery/melonnpan): Model-based Genomically Informed High-dimensional Predictor of Microbial Community Metabolic Profiles
- [gregmedlock/asf_interactions](https://github.com/gregmedlock/asf_interactions): Detection of growth- and metabolism-altering interactions within a defined microbiota

<!-- END CONTENT -->

<!-- ## Follow -->

<!-- list people worth following on social sites (Twitter, LinkedIn, GitHub, YouTube etc.) -->

<!-- Who else should we be following!? -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

<!-- [Thanks goes to these contributors](https://github.com/fawzisal/awesome-metabolic-engineering/graphs/contributors)! -->
