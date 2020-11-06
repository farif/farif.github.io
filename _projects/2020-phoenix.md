---
title: "PHOENIX: Building a Next-gen IDS for cellular devices operating on 4G/LTE."
tool : 'verdict'
date: 2019-2020
collection: projects
permalink: /projects/2020-phoenix
funding: 'Defense Advanced Research Projects Agency (DARPA)'
type: 'IDS, Runtime Verification, LTE'

---
Protocol states machines are susceptible to various attacks where an adversary sending an out of sequence message over the air can manipulate a victim device.  Here are a few examples of these attacks: 
DoS - IMSI cracking 
Eves Dropping - Aka Bypass
Privacy - RLF Report
Spoofing - EMM Information
Wireless broadband communication contains several components:  Core-network that is responsible for all server-side management and base-station responsible for interlinking devices to the core network and devices themselves.  So, the question is where to add the necessary controls to detect such attacks.
The project PHOENIX proposes to provide in-device detection for such high-level attacks.
How: Use syntax guided synthesis problem to synthesis/learn highly descriptive attack signatures from the traffic samples in form of Pastime LTL formulas. These attack signature formulas encode the [generic] behavior of an attack and use runtime monitoring using dynamic programming to monitor the traffic.   

[Tool Link](https://github.com/CLC-UIowa/SySLite)