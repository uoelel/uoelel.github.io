---
title: "Learning resources"
draft: false
description: "Learning resources to teach yourself data analysis and statistics"
---

There are several resources you can use to teach yourself data analysis and statistics skills, depending on your level.
Don't forget to also check the [Research Management](research-skills/) page, for more general research-related skills.

## Beginners

The following resources are suitable for beginners who want to learn data analysis and statistics from scratch.

### Data wrangling and visualisation

* The [R for Data Science](https://r4ds.had.co.nz) (R4DS) free online book is an excellent introduction to R and data analysis.

* The [Data Visualisation Catalogue](https://datavizcatalogue.com/index.html) is a project developed by Severino Ribecca to create a (non-code-based) library of different information visualisation types. The website serves as a learning and inspiration resource for those working with data visualisation.

* The workshop [intRo: Data Analysis with R](https://intro-rstats.github.io) introduces absolute beginners from the Humanities to R, data analysis and visualisation.

### Statistics

* [Statistics for Linguists: An introduction using R](https://discovered.ed.ac.uk/permalink/44UOE_INST/7g3mt6/alma9924344853202466) by Bodo Winter is ideal both for absolute beginners and experienced researchers.
It is packed with everything you need to successfully and effectively conduct statistical analyses.

* [Statistical (Re)thinking](https://discovered.ed.ac.uk/permalink/44UOE_INST/110jsec/alma9924362502302466) by Richard McElreath is an excellent introduction for absolute beginners, by Richard McElreath, which covers a wide variety of linear models.
It focusses on Bayesian inference and how this framework can help us directly answer research questions, assess evidence for different hypothesis, and quantify uncertainty.

* The code from the Statistical (Re)thinking book has been translated into the tidyverse by Solomon Kurz, and it can be accessed here: [Statistical rethinking with brms, ggplot2, and the tidyverse](https://bookdown.org/content/4857/).


----------

## Intermediate

If you have a basic understanding of data analysis, statistics, and R, these resources can help you develop your skills further.

### Dimensionality reduction

If you're data is *highly dimensional*, i.e. you have a lot of different variables, some of which are correlated to each other, you can employ data dimensionality reduction techniques to "synthesise" all the variables into fewer components or clusters.

A common reduction technique is **Principal Component Analysis** (PCA).
This method combines all of your variables into a limited set of numeric *principal components*.
The scores of the principal components capture variation in the data and can be used for further analysis.
You can learn how to carry out a PCA with [this tutorial](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/).

Another dimensionality reduction technique is **Cluster Analysis** (CA, aka hierarchical clustering).
[This tutorial](https://www.datanovia.com/en/blog/cluster-analysis-in-r-practical-guide/) guides you through a CA in R.


### Time series and coordinates

**Generalised Additive (Mixed) Models** are a flexible extension of linear models that allows us to fit non-linear effects.
They are particularly useful with data that come from time series (e.g. f0 and formants, corpus occurrences across time, longitudinal data, etc.) and they can be employed with any kind of data that can be thought of as being represented on a coordinate space (e.g., geolocations, electroencephalographic (EEG) data, 3D tongue imaging, etc).

The tutorial [Generalised additive mixed models for dynamic analysis in linguistics: a practical introduction](https://eprints.whiterose.ac.uk/113858/2/1703_05339v1.pdf) by Márton Sóskuthy is an excellent introduction to Generalised Additive Mixed Models (GAMMs).

Another excellent resource is [Hierarchical generalized additive models in ecology: an introduction with mgcv](https://peerj.com/articles/6876/) by Pedersen and colleagues.
In particular, [Figure 4](https://doi.org/10.7717/peerj.6876/fig-4) is a beautiful visual summary of how different types of trends and groupings can be modelled with GAMs.

The paper [Generalized Additive Mixed Models for intra-speaker variation](https://www.degruyter.com/document/doi/10.1515/lingvan-2016-0030/html) by Tamminga and colleagues advocates for the adoption of GAMMs to advance the use of naturalistic data for studying psycholinguistic questions about intra-speaker variation.

### Bayesian inference

The overview by Etz et al., [How to become a Bayesian in eight easy steps: An annotated reading list](https://doi.org/10.3758/s13423-017-1317-5), is a good place to start from if you want to learn more about Bayesian statistics and inference.

For an more practice-oriented introduction, you should read [Statistical (Re)thinking](https://discovered.ed.ac.uk/permalink/44UOE_INST/110jsec/alma9924362502302466) (see above).

### Phonetics and Speech Sciences

[Functional Data Analysis for Speech Research](http://lands.let.ru.nl/FDA/index.htm) by Michele Gubian is a collection of resources, workshop materials and papers on Functional Data Analysis and **Functional Principal Component Analysis** focussed on speech research data.

The [learnB4SS](https://learnb4ss.github.io) workshop is an introduction to **Bayesian analysis for the Speech Sciences**.
It requires familiarity with linear models and Null Hypothesis Significance Testing.

----------

## Advanced

### Multivariate linear models

[Estimating Multivariate Models with brms](https://cran.r-project.org/web/packages/brms/vignettes/brms_multivariate.html) by Paul Bürkner explains how to fit linear models with two or more outcome variables (i.e. multivariate models) using [brms](https://paul-buerkner.github.io/brms/).
