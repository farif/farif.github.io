---
title: "PHOENIX: Building a Next-gen IDS for cellular devices operating on 4G/LTE"
tool : 'verdict'
date: 2020-10-30 
collection: projects
permalink: /projects/2020-phoenix
funding: 'Defense Advanced Research Projects Agency (DARPA)'
type: 'IDS, LTL, Runtime Verification, LTE'

---
![Little red riding hood](http://farif.github.io/files/projects/warning_system.png)

Protocol states machines are susceptible to various attacks where an adversary sending an out of sequence message over-the-air can manipulate any victim's device. 
Below, we have listed few examples of such attacks:

![Little red riding hood](http://farif.github.io/files/projects/attacks.png)

As an infrastructure, the wireless broadband communication comprises of several components.  The core-network (service provider) is responsible for all server-side management and 
the base-stations are responsible for interlinking devices (UE) to the core network.
Now, the question is how and where to add the necessary controls to detect the attacks on LTE.
The project PHOENIX proposes promises to provide an in-device detection for these kind of behavioral level attacks.
It uses syntax guided synthesis problem to learn highly descriptive attack signatures
(past-time LTL formulas) from the traffic samples. These attack signatures encode the [generic] behavior of an attack and using runtime monitoring using dynamic programming are
efficiently monitor the traffic.   

[Tool Link](https://farif.github.io/tools/2019-phoneix-syslite)