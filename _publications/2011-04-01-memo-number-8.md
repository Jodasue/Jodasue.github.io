---
title: "Toward an execution model for extreme-scale systems-runnemede and beyond"
collection: publications
permalink: /publication/2011-04-01-memo-number-8
excerpt:
date: 2011-04-01
venue: University of Delaware
paperurl:
citation:
---
The Intel-led Ubiquitous High-Performance Computer (UHPC) Runnemede project has been proposed to meet the challenges of the design and development of extreme scale computing systems. It must integrate the combined capabilities of hardware and software technologies in order to yield superior operational attributes. The Runnemede architecture redefines the relationship between memory and processors to provide efficient computation in the presence of drastically disparate cycle times and latencies.

A cornerstone of the UHPC Runnemede project is its program execution model. This technical report provides an overview of the UHPC program execution model. It is intended to serve as a conceptual document in which different UHPC project groups may find a useful common ground. The Runnemede program execution model consists of the following two components: a program (or threading) model, as well as a memory and synchronization model. In summary, the main unique features of the proposed execution model include the following:
- A hierarchical multithreading model featuring a novel event-driven, fine-grain, multithreading
model that is centered on the concepts and semantics of codelets
- Based on the base codelet model above, two types of asynchronous task level parallelism can
be exploited under our execution model
- Type-I asynchronous task parallelism (at the procedure level) : An event-driven, func-
tion/procedure invocation model coupled with split-phase continuations enabled by a codelet based ”sync” back mechanism
- Type II asynchronous task parallelism (at the loop level): an event-driven software pipelining model leveraging an extension of dataflow software pipelining based on codelets
- A shared-address space synchronization model based on an extended location consistency
(LC) model, and the single-assignment principle.

In addition, we provide a brief discussion on means to obtain energy-efficient and resilient program execution through codelet use. Furthermore, the requirements for an appropriate API for the Runnemede program execution model are illustrated through an example. The program execution model and its abstract machine model at Delaware are still evolving rapidly, as such, this technical report constitutes a “work in progress” and is subject to change in the future.
