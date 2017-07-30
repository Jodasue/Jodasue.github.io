---
title: "Designing Scalable Distributed Memory Models: A Case Study"
collection: publications
permalink: /publication/2017-05-15-roofline-number-1
excerpt:
date: 2017-05-15
venue: 'Computing Frontiers 2017'
paperurl: 'http://dl.acm.org/citation.cfm?id=3077425'
citation:
---
One promising effort as we progress toward exascale is the development of fine grain execution models. These models display an innate agility providing new avenues to address the challenges presented by futures systems such as extreme parallelism, restrictive power constraints, and fault tolerance. These opportunities however, may be prematurely abandoned if the system software, particularly a distributed runtime, is incapable of scaling. One potentially limiting factor is the enforcement of the memory model in a runtime.

In a shared memory environment, weaker memory models are preferred since they promote parallelism and optimizations. This is not necessarily the case for distributed systems as a weaker model may lead to increased coherency operations and memory usage based on the application's communication patterns and memory requirements. Moreover, unlike shared memory models which rely on hardware to lessen the costs of coherence, distributed memory models are forced to rely on expensive runtime calls and network operations.

This paper presents the design and implementation of a distributed memory coherency model in a high performance implementation of the Open Community Runtime as an exemplar fine grain execution model. We compare the performance and number of coherence operations of an instance of the OCR standard with our novel model, called Cache DAG consistency (CDAG). Leveraging CDAG consistency, we demonstrate up to a 3.7X reduction in messages and 11x increase in performance for select benchmarks running at scale.
