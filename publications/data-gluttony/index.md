---
author: Reid Dale, Jordan Rodu, Maria E. Currie, Mike Baiocchi
Status: Submitted
sort_date: 2025-08-16
slug: data-gluttony
title: "Data Gluttony: Epistemic Risks, Dependent Testing and Data Reuse in Large Datasets"
categories: Articles
tags:
- Statistics
- Data reuse
details: Submitted
---

Large-scale registries have collected vast amounts of data which has enabled investigators to efficiently conduct studies of observational data. However, we demonstrate how data reuse leads to positive dependence among the inferential tasks and cascading inferential errors. 

Common practice is for investigators to use all data meeting the inclusion criteria of their study to perform their analysis. We term this common practice data gluttony. It has apparent formal justification insofar as this approach maximizes per-study power. But this comes at a cost: data reuse affects the shape of the distribution of inferential errors. Using the theory of risk orderings we demonstrate how positively dependent testing procedures result in strictly riskier distributions of inferential error. 
    
We identify two remedies to this state of affairs: research portfolio optimization and what we term data temperance. Research portfolio optimization requires that we formulate the enterprise of inference in a utility theoretic framework: associated to each hypothesis to be evaluated is some utility dependent on its truth as well as the impact of the statistical decision rendered on the basis of the data. Under certain models of data governance, this approach can be used to optimally allocate data usage across multiple inferential tasks. 

On the other hand, data temperance is a more flexible strategy for managing the distribution of inferential errors. Data temperance is the principle that an investigator use only as much data as is necessary to perform the task at hand. This is possible due to the diminishing marginal returns in power and precision in sample size. In contrast to portfolio optimization, data temperance can be effectively applied in a federated manner. Moreover, we analyze the effectiveness of data temperance at reducing the dependence across testing and develop a theory of the capacity of a static database to sustain large numbers of inferential tasks with low probability of inducing pairwise dependent testing procedures.

Registries are an invaluable resource. We must ensure that they remain valuable by mitigating the risk of cascading inferential errors.