---
title: "Risk estimators for choosing regularization parameters in ill-posed problems - properties and limitations"
date: 2018-10-01
publishDate: 2019-08-13T11:16:23.602320Z
authors: ["Felix Lucka", "Katharina Proksch", "Christoph Brune", "Nicolai Bissantz", "Martin Burger", "Holger Dette", "Frank Wübbeling"]
publication_types: ["2"]
abstract: "This paper discusses the properties of certain risk estimators that recently regained popularity for choosing regularization parameters in ill-posed problems, in particular for sparsity regularization. They apply Stein's unbiased risk estimator (SURE) to estimate the risk in either the space of the unknown variables or in the data space. We will call the latter PSURE in order to distinguish the two different risk functions. It seems intuitive that SURE is more appropriate for ill-posed problems, since the properties in the data space do not tell much about the quality of the reconstruction. We provide theoretical studies of both approaches for linear Tikhonov regularization in a finite dimensional setting and estimate the quality of the risk estimators, which also leads to asymptotic convergence results as the dimension of the problem tends to infinity. Unlike previous works which studied single realizations of image processing problems with a very low degree of ill-posedness, we are interested in the statistical behaviour of the risk estimators for increasing ill-posedness. Interestingly, our theoretical results indicate that the quality of the SURE risk can deteriorate asymptotically for ill-posed problems, which is confirmed by an extensive numerical study. The latter shows that in many cases the SURE estimator leads to extremely small regularization parameters, which obviously cannot stabilize the reconstruction. Similar but less severe issues with respect to robustness also appear for the PSURE estimator, which in comparison to the rather conservative discrepancy principle leads to the conclusion that regularization parameter choice based on unbiased risk estimation is not a reliable procedure for ill-posed problems. A similar numerical study for sparsity regularization demonstrates that the same issue appears in non-linear variational regularization approaches."
featured: false
publication: "*Inverse Problems & Imaging*"
tags: ["Stein's method", "discrepancy principle", "ll-posed  problems", "regularization", "regularization  parameter  choice", "risk  estimators"]
url_pdf: "http://arxiv.org/abs/1701.04970"
doi: "10.3934/ipi.2018047"
---

