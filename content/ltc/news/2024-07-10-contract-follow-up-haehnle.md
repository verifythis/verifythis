---
title: "Contract Languages II: Reiner Hähnle: Context-aware Trace Contracts – 10 July 2024"
author: ulbrich
date: 2024-07-03
---

[Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp) will present work on Context-aware Trace Contracts.

**Time and Date:** *10 July, **16**.00 CEST*, for Link see below.

<!--more-->

As a follow-up to the March 2024 [Lorentz Center workshop on Contract
Languages](https://www.lorentzcenter.nl/contract-languages.html), we
will host a series of online presentations and discussions around
formal methods with contract languages, aligning with the LTC goal of
enabling information exchange between different formal systems.

#### Title
*Context-aware Trace Contracts*,
Joint work with Eduard Kamburjan (U Oslo), Marco Scaletta (TU Darmstadt)

#### Abstract
The behavior of concurrent, asynchronous procedures depends in general on 
the call context, because of the global protocols that govern scheduling. 
This context cannot be specified with the state-based Hoare-style 
contracts common in deductive verification. Recent work generalized 
state-based to trace contracts, which permit to specify internal behavior 
of a procedure, such as calls or state changes, but not its call context. 
In this talk we discuss a program logic of context-aware trace contracts 
for specifying global behavior of asynchronous programs. We also provide a 
sound proof system. To observe the program state not merely at the end 
points of a procedure, we introduce the novel concept of an observation 
binder.
