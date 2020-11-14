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

LTE (control-plane) protocol is susceptible to various attacks either due to a design weakness or an implementation flaw.
Below, we are listing some examples of these attacks and their implications.
![Little red riding hood](http://farif.github.io/files/projects/attacks.png)

The infrastructure of wireless broadband communication comprises of several components.  The core-network (service provider) is responsible for all server-side management, and the base-stations provide a link of communication between any cellular devices (UE) and the core network.

Now, the question is how to add the necessary controls to secure billion of subscribers/users operating on a cellular network (i.e., AT&T, Sprint, T-Mobile and Verizon, etc.).

The project PHOENIX envisions an in-device detection system based that uses syntax-guided synthesis problem to learn attack signatures (past-time LTL formulas) from the network traffic messages. 

These attack signatures encode the [generic] behavior of an attack and provide a lightweight (in-device) monitoring mechanism to alarm users about any ongoing attack.

[Tool Link](https://farif.github.io/tools/2019-phoneix-syslite)