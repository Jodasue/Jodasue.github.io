---
title: "Asynchronous Runtimes in Action: An Introspective Framework for a Next Gen Runtime"
collection: publications
permalink: /publication/2016-08-12-roofline-number-1
excerpt:
date: 2016-05-23
venue: 'IPDRM'
paperurl: 'http://ieeexplore.ieee.org/abstract/document/7530078/'
citation:
---
One of the most critical challenges that new high performance systems face is the lack of system software support for these large scale systems. Investment on system stack components is essential in the development, debugging and optimization of the new emerging programming models. These emerging models have the promise to better utilize the vast hardware resources available in current and future systems. To aid in the development of applications and new system stacks, runtimes, as instances of their respective execution models, need to produce facilities to introspect their inner workings and allow an in depth attribution of performance bottlenecks and computational patterns. In other words, the runtime systems need to reduce their opacity to observers so that users of a novel program execution model can adapt their designs to fit the intended model usage, regardless of the layer that they are working on. This design/development loop (akin to co-design) enables synergistic opportunities across the entire computational stack. This paper presents the design and implementation of a simple"gray" box performance attribution harness running inside a fine grain runtime system: the Open Community Runtime (OCR). We showcase what such a framework can indicate regarding the runtime behavior while running at scale. To this end, we have designed a set of synthetic scenarios aimed to test the runtime at their best and worst cases. We present an analysis of the most important runtime features, properties and idiosyncrasies that will affect the development of new runtime features, algorithmic selection, and application development.
