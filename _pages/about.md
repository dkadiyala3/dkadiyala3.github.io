---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-M9VN5LC2X6"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-M9VN5LC2X6');
</script>  

I am a PhD candidate in the school of [Electrical and Computer Engineering](https://ece.gatech.edu/) at Georgia Tech advised by [Dr. Alexandros Daglis](https://faculty.cc.gatech.edu/~adaglis3/#students), Associate Professor, School of Computer Science.  

My research is focused on developing tailored memory system architectures to enhance the performance of parallel, scientific, and deep learning AI/ML workloads in resource constrained and memory bandwidth-intensive environments. My research draws on insights from computer architecture, memory system design, distributed AI/ML systems, and CXL technologies. 

Prior to joining PhD, I did my Masters in Electrical Engineering from Arizona State University, Tempe and worked full-time as Sr. Applications Engineer at Cadence Design Systems, San Jose, CA. For more details please refer to my [**<u>CV</u>**](files/CV-DivyaKiran_Kadiyala.pdf).


<!---
  - I'm currently seeking full-time opportunities to drive innovation in next-generation memory and distributed system architectures to accelerate parallel and memory bandwidth intensive applications. If you are interested in a collaboration, please reach out to me via email: dkadiyala3@gatech.edu
-->

<div style="border-radius: 12px; padding: 0.75em; margin-top: 0.5em; margin-bottom: 0.5em; background: #FFF5EA; border: 1px solid black; font-size: 0.875em;"> I am currently seeking <strong>full-time opportunities</strong> to advance innovation in next-generation memory and computer system architectures. If my profile aligns with your requirements or areas of interest, please feel free to contact me via <a href="mailto:dkadiyala3@gatech.edu">email</a> or <a href="https://www.linkedin.com/in/divyakirankadiyala/">linkedIn</a></div>

>### Thesis Topic: Memory system optimizations for parallel and bandwidth-intensive applications
>
><div style="text-align: justify; font-size: 0.875em;">
>The growing performance and bandwidth demands of modern datacenter and HPC workloads are driving innovation in memory system design. My research adapts a holistic approach to optimizing memory systems by jointly considering workload-specific characteristics and underlying hardware capabilities. These efforts demonstrate how tailored memory system designs can substantially enhance the performance of parallel, scientific, and deep learning AI applications in resource-constrained and bandwidth-intensive environments.
></div>

<!-- 
I am an Assistant Professor in the [Electrical Engineering and Computer Sciences](https://eecs.berkeley.edu/) department at [UC Berkeley](https://berkeley.edu/). 
Prior to joining Berkeley, I completed my PhD at EPFL in Switzerland and my bachelor's degree at IIT Bombay.

I am a **computer systems** researcher, and my work focuses on developing techniques that
enable engineers to build systems with **well-understood performance and functionality**. 
My research draws on insights from a broad set of domains, including operating systems, networking, computer architecture, and formal methods. 
My work has received several awards, including the [ACM SIGOPS Dennis M. Ritchie Award](https://www.sigops.org/awards/dmr/), the [Eurosys Roger Needham PhD Award](https://www.eurosys.org/awards/roger-needham-phd-award), and the [Dimitris N. Chorafas Award](https://www.weizmann.ac.il/feinberg/about/dimitris-n-chorafas-prize/about-foundation-and-prize), and several of the systems I have helped design have been deployed in production at companies such as Meta and Alibaba. More details can be found in my [CV](files/rishabh-cv.pdf). 

<div style="border-radius: 12px; padding: 0.75em; margin-top: 0.5em; margin-bottom: 0.5em; background: #FFF5EA; border: 1px solid black; font-size: 0.875em;">
  <strong>I am always interested in finding talented and ambitious students to join my group!</strong> For students already at Berkeley, the best way to contact me is via <a href="mailto:rishabh.iyer@berkeley.edu">email</a>. For students seeking to join Berkeley, please refer to the <a href="https://eecs.berkeley.edu/academics/graduate/research-programs/admissions/">Berkeley EECS Graduate Admissions page</a> and mention my name on your application.
</div>

Active Research Directions 
----
Below are a few of my ongoing projects. A full list of my publications can be found [here](/publications).

<div style="border-radius: 12px; padding: 0.75em; margin-top: 0em; margin-bottom: 0.5em; background: #F2FAFF; border: 1px solid black; font-size: 0.85em;">
    <strong> <a href="{{ '/perf-interfaces/' | relative_url }}"> Performance Interfaces for Systems SW & HW:</a></strong>
Semantic interfaces---such as code documentation and specifications---provide simple, abstract descriptions of a system’s functionality, enabling engineers to reason about and use the system’s functionality without having to understand the implementation. In contrast, there exist no equivalent interfaces for system performance, despite performance having become a first-class citizen in system design. <br><br>

The goal of this project is to develop techniques that enable summarizing system performance in succinct yet precise interfaces, allowing engineers to efficiently yet accurately reason about a system's expected performance before it is deployed in production. 
So far, we have demonstrated that it is feasible to realize such performance interfaces for a wide range of low-level systems software and hardware, ranging from packet processing applications [<a href="{{ '/files/pix.pdf' | relative_url }}">PIX</a>], to low-level systems code such as OS system calls and cryptographic libraries [<a href="{{ '/files/cfar.pdf' | relative_url }}">CFAR</a>],
and specialized hardware accelerators for tasks such as deep learning [<a href="{{ '/files/lpn.pdf' | relative_url }}">LTC</a>].
Looking ahead, we are keen to realize such interfaces for large-scale distributed applications and enable efficient reasoning about end-to-end latency and throughput for such applications.
</div>

<div style="border-radius: 12px; padding: 0.75em; margin-top: 1.5em; margin-bottom: 0.5em; background: #F2FAFF; border: 1px solid black; font-size: 0.85em;">
    <strong> <a href="{{ '/files/kflex.pdf' | relative_url }}"> Fast, Flexible, and Practical OS Kernel Extensions:</a></strong>
The ability to safely extend OS kernel functionality is a longstanding goal in OS design, with the widespread use of the
eBPF framework in datacenter infrastructure demonstrating the benefits of such extensibility. Unfortunately, existing solutions
for kernel extensibility (including eBPF) are limited in terms of either the flexibility they offer users or the performance overheads incurred. <br><br>

The goal of this project is to enable engineers to write fast, flexible, and easily deployable kernel extensions. 
As a first step, we built <a href="{{ '/files/kflex.pdf' | relative_url }}">KFlex</a>, a framework that significantly improves the flexibility of eBPF extensions in Linux while incurring negligible performance overheads. 
KFlex is being upstreamed into the Linux kernel mainline and is in the late prototype stage at Meta. 
Looking ahead, we are keen to further push the limits of kernel extensibility and seek to understand whether kernel extensions can be used to not only modify OS policy but also enable structural OS innovations. 
</div>

<div style="border-radius: 12px; padding: 0.75em; margin-top: 1.5em; margin-bottom: 0.5em; background: #F2FAFF; border: 1px solid black; font-size: 0.85em;">
    <strong> Building Reliable and Provably Correct Systems:</strong>
I am also interested in improving system reliability using formal and semi‑formal methods.  
Given the growing criticality of networking infrastructure in modern society, my work in this area has focused on <a href="{{ '/files/hodor.pdf' | relative_url }}">software-defined wide‑area networks</a>, <a href="{{ '/files/vigor.pdf' | relative_url }}">in‑network packet‑processing applications</a>, and <a href="{{ '/files/sublayering.pdf' | relative_url }}">network stacks running on end hosts</a>.

</div>
-->