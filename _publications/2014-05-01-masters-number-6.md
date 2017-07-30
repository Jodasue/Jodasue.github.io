---
title: "DARTS: A Runtime Based on the Codelet Execution Model"
collection: publications
permalink: /publication/2014-05-01-masters-number-6
excerpt:
date: 2014-05-01
venue: University of Delaware
paperurl: 'https://search.proquest.com/openview/060326e15a5c48c46a55bdc9c260ebb0/1?pq-origsite=gscholar&cbl=18750&diss=y'
citation:
---
Over the past decade computer architectures have drastically evolved to circumnavigate prevailing physical limitations in chip technology. Energy consumption and heat expenditure have become the predominant concerns for architects and chip manufacturers. Previously anticipated trends such as frequency scaling, deep execution pipelines, and fully consistent caches in future many-core systems have been deemed unsustainable.

Current architectures are exhibiting new trends including simpler pipelines, lower frequencies, and scratch pad memories. Moreover, these architectures have an ever increasing number of cores. Many predict future architectures to contain thousands of heterogeneous cores on a single die.

With these radical shifts in architectures, current execution models are struggling to adequately scale in performance and newer metrics like energy consumption. The shortcomings of current models have caused some to look back to fine-grained execution models designed for parallelism like dataflow and EARTH. Using these models as inspiration, the Codelet execution model is an event-driven, fine-grained model designed to exploit parallelism while providing efficient mechanism for locality.

In the following, we present the Delaware Asynchronous RunTime System (DARTS), an implementation of the Codelet model. DARTS is a faithful implementation of the Codelet model, providing a vehicle to reason and further develop codelet ideas. It provides two levels of parallelism, event-driven codelets permitting fine-grained parallelism and invoked threaded procedures which ensures locality. Furthermore, the DARTS runtime is built on a reconfigurable abstract machine allowing DARTS to provide performance portability across both architectures and applications. In addition, we provide an in depth analysis of DARTS and its underlying model running on off-the-shelf hardware. Utilizing two x86 machines (both Intel and AMD), we explore the overheads of the codelet model and its implementation using micro benchmarks. Furthermore, we demonstrate DARTS’ performance for two benchmarks, matrix multiply and breadth first search. Leveraging these results, we aim to establish the Codelet model as a promising execution model for future many-core architectures via an efficient and well-designed runtime. The following summarizes the contributions of this thesis:

1. A specification for the Codelet execution model
2. DARTS: An accurate implementation of the Codelet model   
   (a) Two levels of parallelism; fine-grained tasks and procedures intertwined by fine-grain synchronization
   (b) Adaptable abstract machine capable scaling for different applications and hardware
3. A two phase evaluation of DARTS and the Codelet execution model running on available off-the-shelf hardware accomplish by
   (a) Micro benchmarking the base primitives employed by DARTS to realize the Codelet model
   (b) Evaluating case studies on selected benchmarks representative of workloads of interest including matrix multiply and breadth first search
