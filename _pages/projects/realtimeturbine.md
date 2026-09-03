---
title: "AAU TECH Real-time Stream Data Analysis for Offshore Wind Turbine Monitoring"
layout: textlay
excerpt: "ECN AAU -- Projects"
sitemap: false
permalink: /projects/realtimeturbine
---

# Real-time Stream Data Analysis for Offshore Wind Turbine Monitoring

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo_aau.png" style="width: 210px">
</figure>

### Background

Modern wind turbine testing and verification face a series of data intensive challenges that require coordinated advances 
from both data science and electronics research. Wind turbines—especially prototype units—generate massive volumes of 
heterogeneous, high frequency telemetry, including vibration and acoustic data sampled at tens of kilohertz, yet they are 
typically deployed in remote onshore or offshore locations with narrow, failure prone communication channels.

Industry standards such as the IEC 61400 family provide rigorous design, testing, and measurement requirements for loads, 
noise, power performance, electrical characteristics, and communication architectures, forming the backbone of certification 
and data collection practices. Prototype turbines exacerbate data transport constraints because they employ extensive 
instrumentation such as low frequency accelerometers for drivetrain and structural monitoring (e.g., 500 mV/g turbine grade 
accelerometers) and diverse sensing technologies—vibration, speed, temperature, eddy current, and optical fiber Bragg grating 
sensors—that enable high resolution condition monitoring of blades, towers, nacelles, and gearboxes.

### Challenges

Fiber optic and distributed sensing systems are particularly attractive for prototypes because they tolerate harsh offshore 
environments, electromagnetic interference, and lightning, while supporting densely distributed measurement points across long 
structural elements such as blades or drivetrain components. However, moving these high rate multimodal data streams from the 
turbine to the compute layer remains difficult: commercial SCADA systems typically rely on fiber optic LAN or serial links and 
OPC based communication, and offshore wind farm architectures increasingly employ Ethernet based passive optical networks to 
relay turbine telemetry across multiple control layers toward onshore data centers or cloud environments, all of which introduce 
risks of latency, bandwidth saturation, and data corruption when link reliability is low.

These limitations collide with the need to detect extremely low probability failure modes (10⁻³–10⁻⁵), where even small data 
loss events undermine statistical confidence. Further complicating validation is the fact that prototype turbines are few 
(often exactly one), yet their data must generalize to entire future fleets despite substantial uncertainty stemming from sensor 
placement variation, sensor technology variability, structural tolerances, and environmental noise. 

### Impact

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/windturbine-illust.png" width="100%" style="display: block;margin-left: auto;margin-right: auto;margin-top:2rem;">
</figure>

The project is expected to develop reliable, resilient, and performant ML-based solutions to efficiently transmit and analyze 
high-frequency (tens of kHz), high-velocity multimodal data streams, thereby enabling critical-event monitoring of offshore 
wind turbines. This vision creates several research opportunities:

1. **Edge intelligence**—developing on turbine algorithms for feature extraction, denoising, uncertainty quantification, and event detection to minimize data volumes transmitted over constrained links.                                       
2. **Resilient data movement**—designing error tolerant, cybersecure, standards compliant communication layers that respect IEC 61400 communication models while mitigating corruption and synchronizing high rate sensor streams.              
3. **Population level inference from single prototypes**—using Bayesian, physics informed, and simulation augmented models to extrapolate from single unit measurements to expected variability across large turbine populations, while quantifying uncertainty introduced by sensor technology, sensor placement, and data transport imperfections.                         

Combined, these challenges define a rich, interdisciplinary research space at the intersection of data science and electronics, tightly grounded in industry standard practice and modern wind turbine sensing and communication technologies.


|                          |                                                                                                                                                                                                                            |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **People involved**:     | Sokol Kosta (PI), Mustafa Özger(Co-PI), Prof. Christian S. Jensen, Assoc. Prof Tung Kieu, Rifqi Juli Indrayanto (PhD student employed on the project)                                                                                                                                            |
| **Funding source**:      | AAU TECH Strategic Funding                                                                                                                                                                                                 |
| **Budget**:              | € 1.500.000/Year                                                                                                                                                                                                                      |
| **Duration**:            | 01/08/2026 → 31/07/2029                                                                                                                                                                                                    |
| **Partners**:            | Aalborg University                                                                                                                                                                                                         |

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo_aau.png" style="width: 210px">
</figure>