# BIOMD0000000541: MODEL1406130001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000541.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000541.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000541 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Yugi2014 - Insulin induced signalling (PFKL phosphorylation) - model 2

Insulin induces phosphorylation and activation of liver-type
phosphofructokinase 1, which thereby controls a key reaction in glycolysis.
This mechanism is revealed using the mathematical model. In this model, the
PFKL phosphorylation time courses are calculation from the signalling pathway
model developed by Kubata et al. (2012) (
[MODEL1204060000](http://identifiers.org/biomodels.db/MODEL1204060000) \-
Kubota2012_InsulinAction_AKTpathway).

**Author's Note:** Katsuyuki Yugi thank Akira Funahashi (Keio University, Japan) for his kind advice in converting the model from MATLAB to SBML.

This model is described in the article:

[Reconstruction of insulin signal flow from phosphoproteome and metabolome
data.](http://identifiers.org/pubmed/25131207)

Yugi K, Kubota H, Toyoshima Y, Noguchi R, Kawata K, Komori Y, Uda S, Kunida K,
Tomizawa Y, Funato Y, Miki H, Matsumoto M, Nakayama KI, Kashikura K, Endo K,
Ikeda K, Soga T, Kuroda S.

Cell Rep 2014 Aug; 8(4): 1171-1183

Abstract:

Cellular homeostasis is regulated by signals through multiple molecular
networks that include protein phosphorylation and metabolites. However, where
and when the signal flows through a network and regulates homeostasis has not
been explored. We have developed a reconstruction method for the signal flow
based on time-course phosphoproteome and metabolome data, using multiple
databases, and have applied it to acute action of insulin, an important
hormone for metabolic homeostasis. An insulin signal flows through a network,
through signaling pathways that involve 13 protein kinases, 26 phosphorylated
metabolic enzymes, and 35 allosteric effectors, resulting in quantitative
changes in 44 metabolites. Analysis of the network reveals that insulin
induces phosphorylation and activation of liver-type phosphofructokinase 1,
thereby controlling a key reaction in glycolysis. We thus provide a versatile
method of reconstruction of signal flow through the network using
phosphoproteome and metabolome data.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000541](http://identifiers.org/biomodels.db/BIOMD0000000541).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


