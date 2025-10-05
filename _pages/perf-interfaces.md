---
layout: single
title: "Performance Interfaces"
permalink: /perf-interfaces/
author_profile: true
---

Performance interfaces are to performance what semantic interfaces (documentation, header files, specifications, etc.) are to functionality: succinct descriptions of the performance one can expect when running that code. Performance interfaces differ from performance specifications and/or models in that they are succinct and highly accessible to the average developer, in the same way that a semantic interface differs from a formal specification.

Our research pursues three broad directions:
- Extracting performance interfaces from system implementations, and using them to develop applications that meet their performance expectations
- Designing systems that exhibit predictable performance and are thus amenable to being described using a performance interface
- Formally verifying that systems code will indeed perform as advertised by its performance interface

## Publications ##

- **[Automatically Reasoning About How Systems Code Uses the CPU Cache](/files/cfar.pdf)**  
_Rishabh Iyer, Katerina Argyraki, George Candea._ <br>
OSDI 2024. <br>
<span style="color:red">**Also accepted to the Linux Plumbers Conference 2024**</span>.<br>
[[slides]](files/cfar-slides.pptx) [[talk video]](https://www.youtube.com/watch?v=QpgOxTcvCrY)

- **[Performance Interfaces for Hardware Accelerators](/files/lpn.pdf)**  
_Jiacheng Ma, Rishabh Iyer, Sahand Kashani, Mahyar Emami, Thomas Bourgeat, George Candea._<br>
OSDI 2024.<br>
[[slides]](files/lpn-slides.pptx) [[code]](https://github.com/dslab-epfl/lpn) [[talk video]](https://www.youtube.com/watch?v=S6BtXr-bFqk)

- **[Achieving Microsecond-Scale Tail Latency Efficiently with Approximate Optimal Scheduling](/files/concord.pdf)**  
_Rishabh Iyer, Musa Unal, Marios Kogias, George Candea._<br> 
SOSP 2023.<br>
[[slides]](files/concord-slides.pptx) [[code]](https://github.com/dslab-epfl/concord) [[talk video]](https://www.youtube.com/watch?v=VMSdUr-91_U)

- **[Latency Interfaces for Systems Code](files/thesis.pdf)** <br>
_Rishabh Iyer_.<br>
PhD Thesis at EPFL, 2023.

- **[The Case for Performance Interfaces for Hardware Accelerators](/files/perf-interf-accel.pdf)**  
_Rishabh Iyer, Jiacheng Ma, Katerina Argyraki, George Candea, Sylvia Ratnasamy._ <br>
HotOS 2023. <br>
[[slides]](files/accel-hotos-slides.pptx)

- **[Performance Interfaces for Network Functions](/files/pix.pdf)**  
_Rishabh Iyer, Katerina Argyraki, George Candea._ <br> 
NSDI 2022.  <br>
[[slides]](files/pix_slides.pdf) [[talk video]](https://www.youtube.com/watch?v=iM3R2Gp0PWo) [[code]](https://github.com/dslab-epfl/pix)

- **[Performance Contracts for Software Network Functions](/files/bolt.pdf)**  
_Rishabh Iyer, Luis Pedrosa, Arseniy Zaostrovnykh, Solal Pirelli, Katerina Argyraki, George Candea._ <br> 
NSDI 2019.  <br>
[[slides]](files/bolt_slides.pdf) [[talk video]](https://www.youtube.com/watch?v=cV8pCGiTxgQ) [[code]](https://github.com/bolt-perf-contracts/bolt) [[website]](https://bolt-perf-contracts.github.io)


### Software ###

- [**LPN**](https://github.com/dslab-epfl/lpn) is a toolchain that let hardware developers to specify a performance-only model of their hardware accelerators with a representation called Latency Petri Net (_LPN_). The toolchain includes different tools that transform the _LPN_ into different representations for different usages (performance interfaces, verification conditions, fast simulators and formats for visualization).  
- [**PIX**](https://github.com/dslab-epfl/pix) is a toolchain that automatically extracts performance interfaces from software network function (NF) implementations. The resulting performance interfaces are accurate yet orders of magnitude simpler than the code itself, and they take mere minutes to extract. 
- [**Concord**](https://github.com/dslab-epfl/concord) is a runtime that demonstrates how to achieve predictable, microsecond-scale control of execution time with low throughput overhead. 
- [**Bolt**](https://github.com/bolt-perf-contracts/bolt) is a precursor to PIX, and it is used to automatically generate performance contracts for software network functions.

This is a joint project with the [Dependable Systems Lab](https://dslab.epfl.ch) at EPFL. 
