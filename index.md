<h2>About me</h2>
<p>I am a Data Scientist at <a href="https://www.wdgpublichealth.ca">Wellington-Dufferin-Guelph Public Health</a>. I have an MSc (2014) and PhD (2020) in Applied Statistics from the University of Guelph.
  
<p>In my research I navigate the challenges in the statistical modelling of complex population processes. Applications in public health and population ecology are of particular interest to me. This involves me in the study of topics in computational statistics, spatiotemporal models, and individual and agent based models. Much of my recent work has been implemented in open-source software packages.</p>

<details><summary>Current software projects</summary>
<i>Pathogen.jl (2015-present)</i>
<p><a href="https://github.com/jangevaare/Pathogen.jl">Pathogen.jl</a> is an implementation of some of my PhD research into transmission network individual level models of infectious disease, and <a href="https://en.wikipedia.org/wiki/Viral_phylodynamics">phylodynamic</a> models in <a href="https://julialang.org">Julia</a>. It seeks to provide accessible and flexible tools for the simulation, description, visualization, and Bayesian inference of such models. This software provides methods for imputation of event times and transmission networks using data augmentation 

<img src="https://github.com/jangevaare/Pathogen.jl/raw/master/examples/SIR%20Simulation/epiplot.png" width="500"></p>
<i>SubstitutionModels.jl (2017-present)</i>
<p><a href="https://github.com/BioJulia/SubstitutionModels.jl">SubstitutionModels.jl</a> is a package that I&#39;ve contributed to the <a href="https://biojulia.net/Bio.jl/">BioJulia organization</a>. At this time, it provides performant utilities for dealing with nucleic acid substitution models using <a href="https://github.com/JuliaArrays/StaticArrays.jl">StaticArrays.jl</a> and Julia&#39;s <a href="https://docs.julialang.org/en/v1/manual/methods/">multiple dispatch</a>. These models are used for genetic distance calculations, phylogenetic tree construction, genetic sequence simulation, etc.</p>
<i>PhyloTrees.jl (2016-present)</i>
<p><a href="https://github.com/jangevaare/PhyloTrees.jl">PhyloTrees.jl</a> provides a representation of rooted phylogenetic trees in Julia. My eventual goal is to implement Bayesian phylogenetic tree inference using MCMC in Julia with this package. For the time being it has been used in the implementation of phylodynamic models as part of my PhD research.

<img src="https://raw.githubusercontent.com/jangevaare/PhyloTrees.jl/master/treeplot.png" width="500"></p>
<i>GeneticBitArrays.jl (2019-present)</i>
<p><a href="https://github.com/jangevaare/GeneticBitArrays.jl">GeneticBitArrays.jl</a> uses <a href="https://docs.julialang.org/en/v1/base/arrays/#Base.BitArray">Julia&#39;s <code>BitArray</code>s</a> to represent RNA and DNA sequences. This representation is space efficient and highly interpretable. <code>BitArray</code>s also work great with linear algebra in Julia - such as may be used for phylogenetic inference, and simulation of genetic sequences.</p>
<i>PhyloModels.jl (2016-2020)</i>
<p><a href="https://github.com/jangevaare/PhyloModels.jl">PhyloModels.jl</a> builds on my work with <a href="https://github.com/jangevaare/GeneticBitArrays.jl">GeneticBitArrays.jl</a>, <a href="https://github.com/jangevaare/PhyloTrees.jl">PhyloTrees.jl</a>, <a href="https://github.com/BioJulia/SubstitutionModels.jl">SubstitutionModels.jl</a>. It implements <a href="https://doi.org/10.1093%2Fsysbio%2F22.3.240">Felsenstein&#39;s Pruning Algorithm</a> for loglikelihood calculation of phylogenetic trees with aligned genetic sequences at their tips. A <code>Dict</code> with <code>Int64</code> node IDs as keys and <code>GeneticSeq</code> as values is used for input for the loglikelihood calculation, as well as the output from simulation of genetic sequences.
</p>
</details>

<details><summary>Articles</summary>
<i>Published</i>
<ul>
<li><b>Angevaare, J.</b>, Feng, Z. and Deardon, R. (2021) Inference of latent event times and transmission networks in individual level infectious disease models. Spatial and Spatiotemporal Epidemiology. <a href="https://doi.org/10.1016/j.sste.2021.100410">10.1016/j.sste.2021.100410</a> | <a href="https://github.com/jangevaare/jangevaare.github.io/blob/master/TN-ILM%20SSTE%20preprint.pdf">preprint version</a></li>
<li><b>Angevaare, J.</b>, Feng, Z., Deardon, R. (2022) Pathogen.jl: Infectious disease transmission network modelling with Julia. Journal of Statistical Software. <a href="https://doi.org/10.18637/jss.v104.i04">10.18637/jss.v104.i04</a></li>
</ul>
</details>

<details><summary>Proceedings</summary>
<p><ul><li>Rose, D., Edwards, B., Kett, R., Gillis, D., <b>Angevaare, J.</b> (2017) Exploring Anthropogenic Activities and Management Decisions Using a Novel Environmental Agent Based Model. IEEE International Humanitarian Technology Conference, Toronto, ON
</li></ul>
</p></details>
<details><summary>Presentations</summary>
<p>
<ul>
<li><a href="https://github.com/jangevaare/jangevaare.github.io/raw/master/2017%20Epidemics%206%20presentation.pdf"><b>Angevaare, J.<sup>✦</sup></b>, Feng, Z., Deardon, R. (2017) Simulation and inference of phylodynamic individual level models. Epidemics 6 International Conference on Infectious Disease Dynamics. Sitges, Spain (contributed oral presentation)</a></li>
<li><b>Angevaare, J.<sup>✦</sup></b>, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Southwestern Ontario Graduate Mathematics and Statistics Conference, Guelph, ON (contributed poster presentation)</li>
<li><a href="https://github.com/jangevaare/jangevaare.github.io/raw/master/2016%20JSM%20poster.pdf"><b>Angevaare, J.<sup>✦</sup></b>, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Joint Statistical Meetings, Chicago, IL (contributed poster presentation)</a></li>
<li><b>Angevaare, J.<sup>✦</sup></b>, Feng, Z., Deardon, R. (2016) Phylodynamic individual level models: strategies for simulation and inference. Annual Meeting of the Statistical Society of Canada, Brock University, St. Catharines, ON (contributed poster presentation)</li>
<li><a href="https://github.com/jangevaare/jangevaare.github.io/raw/master/2016%20CAVEPM%20poster.pdf"><b>Angevaare, J.<sup>✦</sup></b>, Feng, Z., Deardon, R. (2016) A Phylodynamic extension to individual level models. Canadian Association of Veterinary Epidemiology and Preventive Medicine Conference, University of Guelph, Guelph, ON (contributed poster presentation)</a></li>
<li>Rose, D.<sup>✦</sup>, Kett, R., Yodzis, M., <b>Angevaare, J.</b>, Gillis, D. (2015) A combined agent and stage structured model to investigate anthropogenic activities on a wild fish population. College of Physical and Engineering Science Undergraduate Poster Session, University of Guelph, Guelph, ON (contributed poster presentation)</li>
<li><b>Angevaare, J.<sup>✦</sup></b> (2014) Fitting disease models with likelihoods. Community of Interest in Disease Modelling, University of Guelph, Guelph, ON (oral presentation)</li>
<li><b>Angevaare, J.<sup>✦</sup></b>, Gillis, D., Darlington, G. (2014) Efficient Bayesian Inference for Conditionally Autoregressive Models. Annual Meeting of the Statistical Society of Canada, University of Toronto, Toronto, ON (contributed poster presentation)</li>
<li><b>Angevaare, J.<sup>✦</sup></b>, Gillis, D. (2012). The Utility of Catch Per Unit Effort Variance. Annual Meeting of the Statistical Society of Canada, University of Guelph, Guelph, ON (contributed poster presentation)</li>
<li>Gillis, D.<sup>✦</sup>, <b>Angevaare, J.</b> (2012). Something’s Fishy. Colloquium Joint BIOM&amp;S Seminar Series, University of Guelph, Guelph, ON (invited presentation)</li></ul>
<sup>✦</sup><small>presenting author</small>
</p></details>

<details><summary>Theses</summary>
<p>
<ul>
<li><b>Angevaare, J.</b> (2020) <a href="https://atrium.lib.uoguelph.ca/xmlui/handle/10214/21323">Phylodynamic and Transmission Network Individual Level Infectious Disease Models</a>. Department of Mathematics and Statistics, University of Guelph, Guelph, ON. Doctoral Thesis. Sept 2020. 141 pp. Advisors: <a href="https://zfeng.uoguelph.ca">Prof. Zeny Feng</a>, <a href="https://robdeardon.github.io">Prof. Rob Deardon</a>.
</li>

<li><b>Angevaare, J.</b> (2014) Efficient Bayesian Inference for Conditionally Autoregressive Models. Department of Mathematics and Statistics, University of Guelph, Guelph, ON. Master's Thesis. April 2014. 122 pp. Advisors: <a href="https://danielgillis.wordpress.com">Prof. Daniel Gillis</a>, <a href="https://mathstat.uoguelph.ca/people/darlington">Prof. Gerarda Darlington</a>.
</li>
</ul>
</p></details>

<details><summary>Technical documents</summary>
<p>
<ul>
<li>Gillis, D., Alexander, C., <b>Angevaare, J.</b>, Bakar, C., Cox, R., Kramski, N., Krsic, N. (2014) SON-BP Collaborative Lake Whitefish Research Project: Year 3 report. Technical document.</li>

<li><b>Angevaare, J.</b>, Gillis, D., Cox, R. (2014) SON-BP Collaborative Lake Whitefish Research Project: Milestone 5: Report on Application and Evaluation of Population Models. Technical document. June 2014. 28 pp.</li>

<li><b>Angevaare, J.</b>, Gillis, D. (2014) SON-BP Collaborative Lake Whitefish Research Project: Milestones C3 &amp; C4 - Estimates of Life History and Mortality Parameters of Lake Whitefish (Coregonus clupeaformis). Technical document. January 2014. 15 pp.</li>

<li>Gillis, D., <b>Angevaare, J.</b>, Rueffer, M., Horrocks, J. (2012). Analysis of Total Allowable Catch. Technical document. October 2012. 34 pp.</li>

<li><b>Angevaare, J.</b> (2012) Lake Huron Lake Whitefish Life History Parameters. Technical document. September 2012. 106 pp. (including appendices)</li>
</ul></p></details>

<details><summary>Previous software projects</summary>
<i>FishABM.jl (2014-2015)</i>
<p><a href="https://github.com/jangevaare/FishABM.jl">FishABM.jl</a> was an implementation of a lifecycle model for the application of fisheries management. An age-structured model was used for adults, with options for commercial or recreational harvest. A highly detailed agent based model was used from egg through to juvenilles life stages, grouping individuals from the same brood into an single agent. Movement and various sources of mortality (habitat specific), and the eventual impact on assumptions surrounding movement and mortality on the health of the fishery could be tracked.
</p>
<i>Fisheries_ABM (2014)</i>
<p><a href="https://github.com/jangevaare/Fisheries_ABM">Fisheries_ABM</a> was a prototype for would eventually become <a href="https://github.com/jangevaare/FishABM.jl">FishABM.jl</a>, built in R. It was an stochastic agent based model of a fishery that could account for harvest and anthropogenic mortality sources.
</p>
<i>ILMs.jl (2014-2015)</i>
<p><a href="https://github.com/jangevaare/ILMs.jl">ILMs.jl</a> was my first implementation of individual level models of infectious disease in Julia. It offered simulation and inference in continuous and discrete time, when event times can assumed to be known, for models utilizing power-law infectivity kernel. This package is superceded by my more recent and involved work with <a href="https://github.com/jangevaare/Pathogen.jl">Pathogen.jl</a>. My experience developing this package convinced me to go all-in with Julia for my PhD research.
</p>
<i>ILMPythonTools (2014)</i>
<p><a href="https://github.com/jangevaare/ilmpythontools">ILMPythonTools</a> was an early python implementation of tools for individual level models of infectious disease. This work was stopped in favour of developing such tools instead in <a href="https://julialang.org">Julia</a>.
</p>
</details>

<details><summary>Just for fun</summary>
<i>brew2 (2018-2022)</i>
<p><a href="https://github.com/jangevaare/brew2">brew2</a> is an app built in <a href="https://nodered.org">Node-RED</a> for brewery control using <a href="https://www.raspberrypi.org">Raspberry Pi</a>. It implements sophisticated PID algorithms for mash temperature control using various recirculating mash systems. Its more custom features are written in javascript. Logging uses <a href="https://www.influxdata.com">influxdb</a> time series database.
<br>
<img src="https://github.com/jangevaare/brew2/raw/master/main.png" width="500">
</p>
<i>Various CraftBeerPi3 plugins (2017-2019)</i>
<p>I have developed several popular plugins for <a href="http://web.craftbeerpi.com">CraftBeerPi3</a> brewery control software in python:
<ul><li><a href="https://github.com/jangevaare/cbpi-CascadeControl">CascadeControl</a></li>
<li><a href="https://github.com/jangevaare/cbpi-DependentActor">DependentActor</a></li>
<li><a href="https://github.com/jangevaare/cbpi-OneWireAdvanced">OneWireAdvanced</a></li>
<li><a href="https://github.com/jangevaare/cbpi-OnAtStartup">OnAtStartup</a></li></ul>
</p>
<i>HopScrape (2018)</i>
<p><a href="https://github.com/jangevaare/HopScrape">This project</a> incorporated scraping, and imputation of hop data using <a href="https://www.crummy.com/software/BeautifulSoup/">BeautifulSoup</a>, <a href="https://pandas.pydata.org">pandas</a>, and <a href="https://pypi.org/project/fancyimpute/">fancyimpute</a>. The cleaned and imputed data resulting from this project are available on the repo.
</p>
<i>TriangleDash (2018)</i>
<p><a href="https://github.com/jangevaare/triangledash">TriangleDash</a> is a small application I made to learn <a href="https://plotly.com/dash/">Plotly&#39;s Dash</a>. It is an explanation, calculation, and visualization of results from triangle test sensory analysis.
</p>
<i>Homebrewing PCBs (2018-2020)</i>
<p>I learned a bit about PCB design and electronics, then created a couple board designs for homebrewing applications using Raspberry Pi and ESP8266 IoT devices <a href="https://github.com/jangevaare/Homebrewing-PCBs">and open-sourced them</a>. They can also be purchased from PCBWay.com<sup><a href="https://www.pcbway.com/project/shareproject/ESP8266_Homebrew_v0_1_3.html">1</a>, <a href="https://www.pcbway.com/project/shareproject/Raspberry_Pi_Homebrew_board_v0_2_2.html">2</a></sup>. 100s of these boards have now been produced.
<br>
<img src="pcb1.png" width="250">
<img src="pcb2.png" width="250">
</p></details>


<p>
  <h3>Other profiles:</h3>
  <ul>
  <li><a href="https://arxiv.org/a/angevaare_j_1.html">arXiv</a></li>
  <li><a href="https://github.com/jangevaare">Github</a></li>
  <li><a href="https://www.linkedin.com/in/justinangevaare/">LinkedIn</a></li>
  <li><a href="https://orcid.org/0000-0002-3373-5009">ORCID</a></li>
  <li><a href="https://www.researchgate.net/profile/Justin-Angevaare-2">Research Gate</a></li>
  <li><a href="https://www.semanticscholar.org/author/Justin-B.-J.-Angevaare/30491252">Semantic Scholar</a></li>
</ul>
</p>
