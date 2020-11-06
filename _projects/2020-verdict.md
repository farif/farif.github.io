---
title: "VERDICT - CRV (Cyber Resiliency Verifier)"
tool : 'verdict'
date: 2018-09-30
collection: projects
permalink: /projects/2020-verdict
funding: 'Defense Advanced Research Projects Agency (DARPA)'
type: 'Runtime Verification, Monitors, and Lustre'

---
![Little red riding hood](http://farif.github.io/files/projects/case_program.png)

The project verdict is about building high assurance system designs that are resilient against cyber-attacks using formal verification. In essence, we analyze the system design prior to its' development. 
Methodology: Architecture/interface is specified in AADL while the behavior is encoded using Agree-Annex. 
Attacks are modeled as threat effects and been instrumented within the model and violate the desired behavior safety properties of the system.
Translating the model to the luster program and using the Kind2 model checker, we find concrete violations that exhibit vulnerabilities or susceptible attacks to the design. We pinpoint affected components using the "blame assignment" that contribute to the violation of safety property and "merit assignment" to identify the part of the system used to achieve the assurance. The compositional verification using the assume-guarantee/contract helped us to achieve the scalability required to analyze complex designs.


[Tool Link](https://github.com/ge-high-assurance/VERDICT/)