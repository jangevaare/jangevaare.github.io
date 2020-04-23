# About me
My name is Justin Angevaare. I am a PhD candidate in the Department of Mathematics and Statistics at the University of Guelph.

In my research I seek to navigate the computational challenges in the statistical modelling of complex population processes. Applications in population ecology such as wildlife management and the dynamics of infectious diseases are of particular interest to me. This typically involves me in the study of scientific computing, topics in Bayesian inference, and data visualization.

## Submitted and published articles
**Angevaare, J.**, Feng, Z. and Deardon, R. (2020) Infectious disease transmission network modelling with the Julia language. Submitted to the Journal of Statistical Software [In Review]

**Angevaare, J.**, Feng, Z. and Deardon, R. (2020) Inference of latent event times and transmission networks in individual level infectious disease models. Submitted to Spatial and Spatiotemporal Epidemiology [In Review]

## Proceedings
Rose, D., Edwards, B., Kett, R., Gillis, D., and **Angevaare, J.** (2017) Exploring Anthropogenic Activities and Management Decisions Using a Novel Environmental Agent Based Model. IEEE International Humanitarian Technology Conference, Toronto, ON

## Presentations
**Angevaare, J<sup>✦</sup>**, Feng, Z., Deardon, R. (2017) Simulation and inference of phylodynamic individual level models. Epidemics 6 International Conference on Infectious Disease Dynamics. Sitges, Spain (contributed oral presentation)

**Angevaare, J.<sup>✦</sup>**, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Southwestern Ontario Graduate Mathematics and Statistics Conference, Guelph, ON (contributed poster presentation)

**Angevaare, J.<sup>✦</sup>**, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Joint Statistical Meetings, Chicago, IL (contributed poster presentation)

**Angevaare, J.<sup>✦</sup>**, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Annual Meeting of the Statistical Society of Canada, Brock University, St. Catharines, ON (contributed poster presentation)

**Angevaare, J.<sup>✦</sup>**, Feng, Z., Deardon, R. (2016) A Phylodynamic extension to individual level models. Canadian Association of Veterinary Epidemiology and Preventive Medicine Conference, University of Guelph, Guelph, ON (contributed poster presentation)

Rose, D.<sup>✦</sup>, Kett, R., Yodzis, M., **Angevaare, J.**, Gillis, D. (2015) A combined agent and stage structured model to investigate anthropogenic activities on a wild fish population. College of Physical and Engineering Science Undergraduate Poster Session, University of Guelph, Guelph, ON (contributed poster presentation)

**Angevaare, J.<sup>✦</sup>** (2014) Fitting disease models with likelihoods. Community of Interest in Disease Modelling, University of Guelph, Guelph, ON (oral presentation)

**Angevaare, J.<sup>✦</sup>**, Gillis, D., Darlington, G. (2014) Efficient Bayesian Inference for Conditionally Autoregressive Models. Annual Meeting of the Statistical Society of Canada, University of Toronto, Toronto, ON (contributed poster presentation) 

**Angevaare, J.<sup>✦</sup>**, Gillis, D. (2012). The Utility of Catch Per Unit Effort Variance. Annual Meeting of the Statistical Society of Canada, University of Guelph, Guelph, ON (contributed poster presentation) 

Gillis, D.<sup>✦</sup>, **Angevaare, J.** (2012). Something’s Fishy. Colloquium Joint BIOM&S Seminar Series, University of Guelph, Guelph, ON (invited presentation)

<sup>✦</sup><small>presenting author</small>

## Theses
**Angevaare, J.** (2014) Efficient Bayesian Inference for Conditionally Autoregressive Models. Department of Mathematics and Statistics, University of Guelph, Guelph, ON. Thesis. April 2014. 122 pp.

## Technical documents
Gillis, D., Alexander, C., **Angevaare, J.**, Bakar, C., Cox, R., Kramski, N., Krsic, N. (2014) SON-BP Collaborative Lake Whitefish Research Project: Year 3 report. Technical document. 

**Angevaare, J.**, Gillis, D., Cox, R. (2014) SON-BP Collaborative Lake Whitefish Research Project: Milestone 5: Report on Application and Evaluation of Population Models. Technical document. June 2014. 28 pp. 

**Angevaare, J.**, Gillis, D. (2014) SON-BP Collaborative Lake Whitefish Research Project: Milestones C3 & C4 - Estimates of Life History and Mortality Parameters of Lake Whitefish (Coregonus clupeaformis). Technical document. January 2014. 15 pp. 

Gillis, D., **Angevaare, J.**, Rueffer, M., Horrocks, J. (2012). Analysis of Total Allowable Catch. Technical document. October 2012. 34 pp.

**Angevaare, J.** (2012) Lake Huron Lake Whitefish Life History Parameters. Technical document. September 2012. 106 pp. (including appendices)

## Current software projects
### Pathogen.jl (2015-present)
[Pathogen.jl](https://github.com/jangevaare/Pathogen.jl) is an implementation of some of my PhD research into transmission network individual level models of infectious disease, and [phylodynamic](https://en.wikipedia.org/wiki/Viral_phylodynamics) models. It seeks to provide accessible tools for the simulation, description, visualization, and Bayesian inference of such models. Imputation of event times using data augmentation 

<img src="https://github.com/jangevaare/Pathogen.jl/raw/master/examples/SIR%20Simulation/epiplot.png" width="500">

### SubstitutionModels.jl (2017-present)
[SubstitutionModels.jl](https://github.com/BioJulia/SubstitutionModels.jl) is a package that I've contributed to the [BioJulia organization](https://biojulia.net/Bio.jl/). At this time, it provides performant utilities for dealing with nucleic acid substitution models using [StaticArrays.jl](https://github.com/JuliaArrays/StaticArrays.jl) and Julia's [multiple dispatch](https://docs.julialang.org/en/v1/manual/methods/). These models are used for genetic distance calculations, phylogenetic tree construction, genetic sequence simulation, etc.

### PhyloTrees.jl (2016-present)
[PhyloTrees.jl](https://github.com/jangevaare/PhyloTrees.jl) is a basic representation of rooted phylogenetic trees in Julia. My eventual goal is to implement Bayesian phylogenetic tree inference using MCMC in Julia, using this package. For the time being it has been used in the implementation of phylodynamic models as part of my PhD research.

<img src="https://raw.githubusercontent.com/jangevaare/PhyloTrees.jl/master/treeplot.png" width="500">

### GeneticBitArrays.jl (2019-present)
[GeneticBitArrays.jl](https://github.com/jangevaare/GeneticBitArrays.jl) uses [Julia's `BitArray`s](https://docs.julialang.org/en/v1/base/arrays/#Base.BitArray) to represent RNA and DNA sequences. This representation is space efficient and highly interpretable. Also, promotion in Julia, makes for succinct usage of `GeneticBitArrays` with linear algebra - such as may be used for phylogenetic inference, and simulation of genetic sequences.

### PhyloModels.jl (2016-2020)
[PhyloModels.jl](https://github.com/jangevaare/PhyloModels.jl) builds on my work with [GeneticBitArrays.jl](https://github.com/jangevaare/GeneticBitArrays.jl), [PhyloTrees.jl](https://github.com/jangevaare/PhyloTrees.jl), [SubstitutionModels.jl](https://github.com/BioJulia/SubstitutionModels.jl). It implements [Felsenstein's Pruning Algorithm](https://doi.org/10.1093%2Fsysbio%2F22.3.240) for loglikelihood calculation of phylogenetic trees with aligned genetic sequences, at their tips. A `Dict` with `Int64` node IDs as keys and `GeneticSeq` as values is used for input for the loglikelihood calculation, as well as the output from simulation of genetic sequences.

## Past software projects
### FishABM.jl (2014-2015)
[FishABM.jl](https://github.com/jangevaare/FishABM.jl) is an implementation of a lifecycle model that has applications for fisheries management. An age-structured model is used for adults, with options for commercial or recreational harvest. A highly detailed agent based model are used from egg through to juvenilles life stages, grouping individuals from the same brood into an single agent. Movement and various sources of mortality (habitat specific), and the eventual impact on assumptions surrounding movement and mortality on the health of the fishery can be tracked.

### Fisheries_ABM (2014)
[Fisheries_ABM](https://github.com/jangevaare/Fisheries_ABM) is a prototype for what would eventually be [FishABM.jl](https://github.com/jangevaare/FishABM.jl), built in R. It was an stochastic agent based model of a fishery which could account for harvest and anthropogenic mortality sources.

### ILMs.jl (2014-2015)
[ILMs.jl](https://github.com/jangevaare/ILMs.jl) was my first implementation of individual level models of infectious disease in Julia. It offers simulation and inference in continuous and discrete time, when event times can be assumed to be known, for models utilizing power-law infectivity kernel. This package is superceded by my more recent and involved work with [Pathogen.jl](https://github.com/jangevaare/Pathogen.jl). My experience developing this package convinced me to go all-in with Julia for my PhD research.

### ILMPythonTools (2014)
[ILMPythonTools](https://github.com/jangevaare/ilmpythontools) was an early python implementation of tools for individual level models of infectious disease. This work was stopped in favour of developing such tools instead in [Julia](https://julialang.org).

## Just for fun projects
### brew2 (2018-present)
brew2 is an app built in [Node-RED](https://nodered.org) for brewery control using [Raspberry Pi](https://www.raspberrypi.org). It implements sophisticated PID algorithms for mash temperature control using various recirculating mash systems. It's more custom features are written in javascript. Logging uses [influxdb](https://www.influxdata.com) time series database.

<img src="https://github.com/jangevaare/brew2/raw/master/main.png" width="500">

### Various CraftBeerPi3 plugins (2017-2019)
I have developed several popular plugins for [CraftBeerPi3](http://web.craftbeerpi.com) brewery control software in python:
* [CascadeControl](https://github.com/jangevaare/cbpi-CascadeControl)
* [DependentActor](https://github.com/jangevaare/cbpi-DependentActor)
* [OneWireAdvanced](https://github.com/jangevaare/cbpi-OneWireAdvanced)
* [OnAtStartup](https://github.com/jangevaare/cbpi-OnAtStartup)

### HopScrape (2018)
[This project](https://github.com/jangevaare/HopScrape) incorporated scraping, and imputation of hop data using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/), [pandas](https://pandas.pydata.org), and [fancyimpute](https://pypi.org/project/fancyimpute/). The cleaned and imputed data resulting from this project are available on the repo.

### TriangleDash (2018)
[TriangleDash](https://github.com/jangevaare/triangledash) is a small application I made to learn [Plotly's Dash](https://plotly.com/dash/). It is an explanation, calculation, and visualization of results from triangle test sensory analysis. It's deployed and can be used here: https://triangledash.herokuapp.com

### Homebrewing PCBs (2018-Current)
I learned a bit about PCB design and electronics, then created a couple board designs for homebrewing applications and open-sourced them. The source files can be found in [this repository](https://github.com/jangevaare/Homebrewing-PCBs). They can also be purchased from PCBS.io and PCBWay.com (links on repo). 100s of these boards have now been produced.

<img src="https://file.pcbway.com/websponsor/18/09/20/102643656_Top.png" width="250">
