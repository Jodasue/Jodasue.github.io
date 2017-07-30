---
title: "Application Characterization at Scale: Lessons Learned from Developing a Distributed Open Community Runtime System for High Performance Computing"
collection: publications
permalink: /publication/2016-05-16-character-number-4
excerpt:
date: 2016-05-16
venue: 'Computing Frontiers 2016'
paperurl: 'http://dl.acm.org/citation.cfm?id=2903166'
citation:
---
Since 2012, the U.S. Department of Energy's X-Stack program has been developing solutions including runtime systems, programming models, languages, compilers, and tools for the Exascale system software to address crucial performance and power requirements. Fine grain programming models and runtime systems show a great potential to efficiently utilize the underlying hardware. Thus, they are essential to many X-Stack efforts. An abundant amount of small tasks can better utilize the vast parallelism available on current and future machines. Moreover, finer tasks can recover faster and adapt better, due to a decrease in state and control.

Nevertheless, current applications have been written to exploit old paradigms (such as Communicating Sequential Processor and Bulk Synchronous Parallel processing). To fully utilize the advantages of these new systems, applications need to be adapted to these new paradigms. As part of the applications' porting process, in-depth characterization studies, focused on both application characteristics and runtime features, need to take place to fully understand the application performance bottlenecks and how to resolve them.

This paper presents a characterization study for a novel high performance runtime system, called the Open Community Runtime, using key HPC kernels as its vehicle. This study has the following contributions: one of the first high performance, fine grain, distributed memory runtime system implementing the OCR standard (version 0.99a); and a characterization study of key HPC kernels in terms of runtime primitives running on both intra and inter node environments. Running on a general purpose cluster, we have found up to 1635x relative speed-up for a parallel tiled Cholesky Kernels on 128 nodes with 16 cores each and a 1864x relative speed-up for a parallel tiled Smith-Waterman kernel on 128 nodes with 30 cores.
