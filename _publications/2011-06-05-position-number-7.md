---
title: "Using a Codelet Program Execution Model for Exascale Machines: Position Paper"
collection: publications
permalink: /publication/2011-06-05-position-number-7
excerpt:
date: 2011-06-05
venue: 'EXADAPT'
paperurl: 'http://dl.acm.org/citation.cfm?id=2000424'
citation:
---
As computing has moved relentlessly through giga-, tera-, and peta-scale systems, exa-scale (a million trillion operations/sec.) computing is currently under active research. DARPA has recently sponsored the "UHPC" [1] --- ubiquitous high-performance computing --- program, encouraging partnership with academia and industry to explore such systems. Among the requirements are the development of novel techniques in "self-awareness"in support of performance, energy-efficiency, and resiliency.

Trends in processor and system architecture, driven by power and complexity, point us toward very high-core-count designs and extreme software parallelism to solve exascaleclass problems. Our research is exploring a fine-grain, event-driven model in support of adaptive operation of these machines. We are developing a Codelet Program Execution Model which breaks applications into codelets (small bits of functionality) and dependencies (control and data) between these objects. It then uses this decomposition to accomplish advanced scheduling, to accommodate code and data motion within the system, and to permit flexible exploitation of parallelism in support of goals for performance and power.
