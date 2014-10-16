# MODEL1112050001: Liu2009_GlucoseMobilization_UptakeModel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1112050001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1112050001.git@20140916`

## Usage

Importing the model package.

`import MODEL1112050001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A molecular mathematical model of glucose mobilization and uptake.**   
Liu W, Hsin C, Tang F. _Math Biosci._ 2009 Oct;221(2):121-9.
[19651146](http://www.ncbi.nlm.nih.gov/pubmed/19651146) ,  
**Abstract:**   
A new molecular mathematical model is developed by considering the kinetics of
GLUT2, GLUT3, and GLUT4, the process of glucose mobilization by glycogen
phosphorylase and glycogen synthase in liver, and the dynamics of the insulin
signaling pathway. The new model can qualitatively reproduce the experimental
glucose and insulin data. It also enables us to use the Bendixson criterion
about the existence of periodic orbits of a two-dimensional dynamical system
to mathematically predict that the oscillations of glucose and insulin are not
caused by liver, instead they would be caused by the mechanism of insulin
secretion from pancreatic beta cells. Furthermore it enables us to conduct a
parametric sensitivity analysis. The analysis shows that both glucose and
insulin are most sensitive to the rate constant for conversion of
PI(3,4,5)P(3) to PI(4,5)P(2), the multiplicative factor modulating the rate
constant for conversion of PI(3,4,5)P(3) to PI(4,5)P(2), the multiplicative
factor that modulates insulin receptor dephosphorylation rate, and the maximum
velocity of GLUT4. Moreover, the sensitivity analysis predicts that an
increase of the apparent velocity of GLUT4, a combination of elevated
mobilization rate of GLUT4 to the plasma membrane and an extended duration of
GLUT4 on the plasma membrane, will result in a decrease in the needs of plasma
insulin. On the other hand, an increase of the GLUT4 internalization rate
results in an elevated demand of insulin to stimulate the mobilization of
GLUT4 from the intracellular store to the plasma membrane.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


