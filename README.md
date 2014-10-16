# BIOMD0000000353: Nag2011_ChloroplasticStarchDegradation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000353.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000353.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000353 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Kinetic modeling and exploratory numerical simulation of chloroplastic starch degradation. **   
Nag A, Lunacek M, Graf PA, Chang CH. _BMC Syst Biol._2011 Jun 18;5:94.
[21682905](http://www.ncbi.nlm.nih.gov/pubmed/21682905),  
**Abstract:**   
BACKGROUND: Higher plants and algae are able to fix atmospheric carbon dioxide
through photosynthesis and store this fixed carbon in large quantities as
starch, which can be hydrolyzed into sugars serving as feedstock for
fermentation to biofuels and precursors. Rational engineering of carbon flow
in plant cells requires a greater understanding of how starch breakdown fluxes
respond to variations in enzyme concentrations, kinetic parameters, and
metabolite concentrations. We have therefore developed and simulated a
detailed kinetic ordinary differential equation model of the degradation
pathways for starch synthesized in plants and green algae, which to our
knowledge is the most complete such model reported to date. RESULTS:
Simulation with 9 internal metabolites and 8 external metabolites, the
concentrations of the latter fixed at reasonable biochemical values, leads to
a single reference solution showing β-amylase activity to be the rate-limiting
step in carbon flow from starch degradation. Additionally, the response
coefficients for stromal glucose to the glucose transporter kcat and KM are
substantial, whereas those for cytosolic glucose are not, consistent with a
kinetic bottleneck due to transport. Response coefficient norms show stromal
maltopentaose and cytosolic glucosylated arabinogalactan to be the most and
least globally sensitive metabolites, respectively, and β-amylase kcat and KM
for starch to be the kinetic parameters with the largest aggregate effect on
metabolite concentrations as a whole. The latter kinetic parameters, together
with those for glucose transport, have the greatest effect on stromal glucose,
which is a precursor for biofuel synthetic pathways. Exploration of the
steady-state solution space with respect to concentrations of 6 external
metabolites and 8 dynamic metabolite concentrations show that stromal
metabolism is strongly coupled to starch levels, and that transport between
compartments serves to lower coupling between metabolic subsystems in
different compartments. CONCLUSIONS: We find that in the reference steady
state, starch cleavage is the most significant determinant of carbon flux,
with turnover of oligosaccharides playing a secondary role. Independence of
stationary point with respect to initial dynamic variable values confirms a
unique stationary point in the phase space of dynamically varying
concentrations of the model network. Stromal maltooligosaccharide metabolism
was highly coupled to the available starch concentration. From the most highly
converged trajectories, distances between unique fixed points of phase spaces
show that cytosolic maltose levels depend on the total concentrations of
arabinogalactan and glucose present in the cytosol. In addition, cellular
compartmentalization serves to dampen much, but not all, of the effects of one
subnetwork on another, such that kinetic modeling of single compartments would
likely capture most dynamics that are fast on the timescale of the transport
reactions.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


