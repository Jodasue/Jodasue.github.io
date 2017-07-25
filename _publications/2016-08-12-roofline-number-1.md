---
title: "Extending the Roofline Model for Asynchronous Many-Task Runtimes"
collection: publications
permalink: /publication/2016-08-12-roofline-number-1
excerpt:
date: 2016-08-12
venue: 'CLUSTER 2016'
paperurl: 'http://ieeexplore.ieee.org/abstract/document/7776548/'
citation:
---
A common practice for application developers is to experimentally determine the granularity of a task after a code has been parallelized based on the observed overhead of a runtime. Instead, we propose a new methodology based on an extended Roofline model to provide practical upper bounds on the throughput performance of an application. First, we extend the Roofline model to support not only latency hiding analysis, but also a multidimensional amortized analysis. By combining this new methodology with a serial application and an Asynchronous Many Task (AMT) runtime implementation, we can predict the worst case runtime overhead attribution of individual runtime features prior to the development of parallel code.
