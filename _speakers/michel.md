---
name: Oliver Michel
title: Oliver Michel
affiliation: Illinois Institute of Technology
web: https://olivermichel.github.io
bio: |
    Oliver Michel is an Assistant Professor of Computer Science at the Illinois Institute of Technology. He received a Ph.D. in Computer Science from the University of Colorado Boulder, advised by Professor Eric Keller, and a B.Sc. in Computer Science from the University of Vienna. Prior to joining IIT, he was an Associate Research Scholar at Princeton University working with Professor Jennifer Rexford.  His research focuses on measuring and optimizing networks for emerging, low-latency, interactive networked applications, such as AR/VR and video conferencing. His measurement studies and system designs span the entire stack from rich, user-facing applications to the physical-layer intricacies of wireless access networks. Michel’s work has been published in top-tier venues, including SIGCOMM, NSDI, IMC, ATC, and HotNets.
description: Scalable Video Conferencing using SDN Principles
abstract: |
      Real-time communications applications such as video conferencing face an unwavering surge in traffic, stressing their underlying infrastructure in unprecedented ways. This work rethinks the key building block for conferencing infrastructures — selective forwarding units (SFUs). SFUs relay and adapt media streams between participants and, today, run in software on general-purpose servers. Our main insight, discerned from dissecting the operation of production SFU servers, is that SFUs largely mimic traditional packet-processing operations such as dropping and forwarding. Guided by this, we present Scallop, an SDN-inspired SFU that decouples video-conferencing applications into a hardware-based data plane for latency-sensitive and frequent media operations, and a software control plane for the (infrequent) remaining tasks, such as analyzing feedback signals and session management. Scallop is a general design that is suitable for a variety of hardware platforms, including programmable switches and SmartNICs. Our Tofino-based implementation fully supports WebRTC and delivers 7-422× improved scaling over a 32-core commodity server, while reaping performance improvements by cutting forwarding-induced latency by 26×.
img: michel.jpeg
affil_img: illinois_tech.png
keynote: false
---