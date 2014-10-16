# BIOMD0000000089: Locke2006_CircClock_LL

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000089.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000089.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000089 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Experimental validation of a predicted feedback loop in the multi-oscillator clock of Arabidopsis thaliana.**   
Locke JC, Kozma-Bognár L, Gould PD, Fehér B, Kevei E, Nagy F, Turner MS, Hall
A, Millar AJ _Mol. Syst. Biol._ 2006;Volume:2;Page:59
[17102804](http://www.ncbi.nlm.nih.gov/pubmed/17102804) ,  
**Abstract:**   
Our computational model of the circadian clock comprised the feedback loop
between LATE ELONGATED HYPOCOTYL (LHY), CIRCADIAN CLOCK ASSOCIATED 1 (CCA1)
and TIMING OF CAB EXPRESSION 1 (TOC1), and a predicted, interlocking feedback
loop involving TOC1 and a hypothetical component Y. Experiments based on model
predictions suggested GIGANTEA (GI) as a candidate for Y. We now extend the
model to include a recently demonstrated feedback loop between the TOC1
homologues PSEUDO-RESPONSE REGULATOR 7 (PRR7), PRR9 and LHY and CCA1. This
three-loop network explains the rhythmic phenotype of toc1 mutant alleles.
Model predictions fit closely to new data on the gi;lhy;cca1 mutant, which
confirm that GI is a major contributor to Y function. Analysis of the three-
loop network suggests that the plant clock consists of morning and evening
oscillators, coupled intracellularly, which may be analogous to coupled,
morning and evening clock cells in Drosophila and the mouse.

  

The model describes a three loops model of the Arabidopsis circadian clock. It
provides initial conditions, parameter values and reactions for the production
rates of the following species: LHY mRNA (cLm), cytoplasmic LHY (cLc), nuclear
LHY (cLn), TOC1 mRNA (cTm), cytoplasmic TOC1 (cTc), nuclear TOC1 (cTn), X mRNA
(cXm), cytoplasmic X (cXc), nuclear X (cXn), Y mRNA (cYm), cytoplasmic Y
(cYc), nuclear Y (cYn), nuclear P (cPn), APRR7/9 mRNA, cytoplasmic APRR7/9,
and nuclear APRR7/9.

The paper describes the behaviour of the model in constant light (LL) and day-
night cycle (LD). However, the current model only contains the LL cycle. Some
parameter values should be changed from the wild-type (WT) ones in order to
simulate the effect of mutations. These changes are listed in the notes of
relevant parameters.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


