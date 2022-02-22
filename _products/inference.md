---
title: "Encrypted Traffic Inference"
date: 2022-02-17T12:33:46+10:00
featured: true
weight: 1
short: NetMicroscope infers information about network performance and activity even when traffic is encrypted.
---

# Encrypted Traffic and Application Quality Inference

<div class="row">
  <div class="col-lg-4">
    <p>
      Video streaming comprises more than 75 percent of today's Internet
      traffic.  Accurately measuring the quality of experience of such
      service, both in broadband and cellular networks, is paramount.  Such
      measurement helps ISPs detect performance issues, preferably before
      customers make calls about degraded service. This allows ISPs to take
      proactive actions that can improve service performance, such as
      re-routing a stream over a less congested path.
    </p>
  </div>

  <div class="col-lg-8">
    <img class="img-fluid rounded mb-4" src="/images/products/NetMicroscopeDiagram.jpg" alt="NetMicroscope diagram">
  </div>
</div>

Yet, inferring the quality of an application's service on a network is
challenging. This requires both domain expertise in networking, deep
understanding of the target application, and systems/DevOps
capabilities.  Meanwhile, ISPs are spending a massive amount of money
on running customer call centers without good answers to provide: not
because the lack data but because the lack of an efficient and accurate
video QoE monitoring solution.

**NetMicroscope** is a system that accurately infers video streaming quality metrics in
real time, such as startup delay or video resolution, by using just a
handful of features extracted from passive traffic measurement. Network
Microscope passively collects a corpus of network features about the
traffic flows of interest in the network and directs those to a
real-time analytics framework that can perform more complex inference
tasks. Network Microscope enables network operators to determine
degradations in application quality as they happen, even when the
traffic is encrypted. 

## Publications 

*Inferring Streaming Video Quality from Encrypted Traffic: Practical Models and Deployment Experience*<br/>
[[paper (pdf)]](https://dl.acm.org/doi/abs/10.1145/3366704)<br/>
F. Bronzino, P. Schmitt, S.Ayoubi, G. Martins, R. Teixeira, N. Feamster.<br/>
Proceedings of the ACM on Measurement and Analysis of Computing Systems (POMACS) and at ACM Sigmetrics 2020, Boston, USA, June 8-12, 2020.


*Traffic Refinery: Cost-Aware Data Representation for Machine Learning on Network Traffic*<br/>
[[paper (pdf)]](https://dl.acm.org/doi/abs/10.1145/3491052)<br/>
F. Bronzino, P. Schmitt, S.Ayoubi, H. Kim, R. Teixeira, N. Feamster.<br/>
Proceedings of the ACM on Measurement and Analysis of Computing Systems (POMACS) and at ACM Sigmetrics 2022, Mumbai, India, June 6-10, 2022.