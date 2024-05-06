---
layout: talk
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

_Full publication list on [Google Scholar](https://scholar.google.com/citations?user=0RVMZkUAAAAJ&hl=en)_

## Erasure detection of a dual-rail qubit encoded in a double-post superconducting cavity
Akshay Koottandavida<sup>*</sup>, Ioannis Tsioutsios <sup>*</sup>, Aikaterini Kargioti, Cassady R. Smith, Vidul R. Joshi, Wei Dai, James D. Teoh, Jacob C. Curtis, Luigi Frunzio, Robert J. Schoelkopf, and Michel H. Devoret, 

Journal : Physical Review Letters \
Date : 2024-05-03 \
DOI : 10.1103/PhysRevLett.132.180601

 Qubits with predominantly erasure errors present distinctive advantages for quantum error correction (QEC) and fault-tolerant quantum computing. Logical qubits based on dual-rail encoding that exploit erasure detection have been recently proposed in superconducting circuit architectures, with either coupled transmons or cavities. Here, we implement a dual-rail qubit encoded in a compact, double-post superconducting cavity. Using an auxiliary transmon, we perform erasure detection on the dual-rail subspace. We characterize the behavior of the code space by a novel method to perform joint-Wigner tomography. This is based on modifying the cross-Kerr interaction between the cavity modes and the transmon. We measure an erasure rate of 3.981±0.003 (ms)−1 and a residual, postselected dephasing error rate up to 0.17 (ms)−1 within the code space. This strong hierarchy of error rates, together with the compact and hardware-efficient nature of this novel architecture, holds promise in realizing QEC schemes with enhanced thresholds and improved scaling.

## Unraveling the topology of dissipative quantum systems
Clemens Gneiting, Akshay Koottandavida, A. V. Rozhkov, and Franco Nori

Journal : Physical Review Research \
Date : 2022-04-12 \
DOI : 10.1103/PhysRevResearch.4.023036

We discuss topology in dissipative quantum systems from the perspective of quantum trajectories. The latter emerge in the unraveling of Markovian quantum master equations and/or in continuous quantum measurements. Ensemble-averaging quantum trajectories at the occurrence of quantum jumps, i.e., the jump times, gives rise to a discrete, deterministic evolution which is highly sensitive to the presence of dark states [Gneiting et al., Phys. Rev. A 104, 062212 (2021)]. We show for a broad family of translation-invariant collapse models that the set of dark-state-inducing Hamiltonians imposes a nontrivial topological structure on the space of Hamiltonians, which is also reflected by the corresponding jump-time dynamics. The topological character of the latter can then be observed, for instance, in the transport behavior, exposing an infinite hierarchy of topological phase transitions. We develop our theory for one- and two-dimensional two-band Hamiltonians and show that the topological behavior is directly manifest for chiral, PT, or time-reversal-symmetric Hamiltonians.



## Nonreciprocal reconfigurable microwave optomechanical circuit
N.R. Bernier*, L.D. Tóth*, A. Koottandavida, M. A. Ioannou, D. Malz, A. Nunnenkamp, A.K. Feofanov & T.J. Kippenberg

Journal : Nature Communications \
Date : 2017-09-19 \
DOI : 10.1038/s41467-017-00447-1

Nonreciprocal microwave devices are ubiquitous in radar and radio communication and indispensable in the readout chains of superconducting quantum circuits. Since they commonly rely on ferrite materials requiring large magnetic fields that make them bulky and lossy, there has been significant interest in magnetic-field-free on-chip alternatives, such as those recently implemented using the Josephson nonlinearity. Here, we realize reconfigurable nonreciprocal transmission between two microwave modes using purely optomechanical interactions in a superconducting electromechanical circuit. The scheme relies on the interference in two mechanical modes that mediate coupling between the microwave cavities and requires no magnetic field. We analyse the isolation, transmission and the noise properties of this nonreciprocal circuit. Finally, we show how quantum-limited circulators can be realized with the same principle. All-optomechanically mediated nonreciprocity demonstrated here can also be extended to directional amplifiers, and it forms the basis towards realizing topological states of light and sound.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Authors contributed equally to this work
