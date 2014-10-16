# BIOMD0000000253: Teusink1998_Glycolysis_TurboDesign

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000253.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000253.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000253 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the model described in the article:  
**The danger of metabolic pathways with turbo design**   
Teusink B, Walsh MC, van Dam K, Westerhoff HV _Trends Biochem. Sci._ 1998 May;
Volume: 23 (Issue: 5 ): 162-9
[9612078](http://www.ncbi.nlm.nih.gov/pubmed/9612078) ,  
**Abstract:**   
Many catabolic pathways begin with an ATP-requiring activation step, after
which further metabolism yields a surplus of ATP. Such a 'turbo' principle is
useful but also contains an inherent risk. This is illustrated by a detailed
kinetic analysis of a paradoxical Saccharomyces cerevisiae mutant; the mutant
fails to grow on glucose because of overactive initial enzymes of glycolysis,
but is defective only in an enzyme (trehalose 6-phosphate synthase) that
appears to have little relevance to glycolysis. The ubiquity of pathways that
possess an initial activation step, suggests that there might be many more
genes that, when deleted, cause rather paradoxical regulation phenotypes (i.e.
growth defects caused by enhanced utilization of growth substrate).

The model represents the wild-type cell: 'guarded' glycolysis, which is the
inhibition of the HK module by hexose monophosphate. The model reproduces
figures 3c and 3d of the reference publication.

To reproduce unguarded glycolysis, set parameter wild_type to '0'.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


