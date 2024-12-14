---
title: "Cluster RCT Design Optimization"
excerpt: "Simulation study optimizing cluster randomized trial designs through cost-benefit analysis<br/><img src='/images/cluster-simulation.png'>"
collection: portfolio
---

![Figure 5](images/cluster_fig5.png)

This simulation study investigates optimal design choices in cluster randomized controlled trials (cRCTs) under budget constraints. Using parallel computing and statistical modeling in R, I investigated how to optimize the tradeoff between number of clusters and cluster size when factors like cost ratios, between-cluster variance, and within-cluster variance vary. The analysis revealed that while optimal designs are primarily driven by cost ratios between adding clusters versus increasing cluster size, variance components influence designs in unexpectedly complex ways. The study implemented both univariate sensitivity analyses and full factorial designs for both normal and Poisson outcomes, employing the ADEMP framework in simulation design. 

Keywords: Academic project, Simulation study, Hierarchical modeling

[View project on GitHub](https://github.com/tomrannosaurus/cluster_RCT_sim)​​​​​​​​​​​​​​​​