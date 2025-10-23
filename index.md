---
title: NRV Framework
subtitle: logo
---

## The NRV Framework - a brief introduction

NRV (NeuRon Virtualizer) is a Python-based framework designed to enable fast and user-friendly simulations of the Peripheral Nervous System. Computations are performed under the quasistatic approximation of Maxwell’s equations, and ephaptic coupling is not considered. Stimulation waveforms can have arbitrary shapes, and any combination of electrodes can be used to model complex stimulation strategies. NRV simulates the physics associated to: electrical stimulation, extracellular potentials as well as bio-impedance of single fiber to complex and geometrically-detailed full nerve structures.

NRV is optimized for simulations involving large axon populations—from generating realistic axon populations based on specific diameter distributions, to automated spatial placement, computation, and post-processing of axonal responses to stimulation. Parallel computation and interfaces with NEURON (used for neural dynamics), and FEniCS (used for Finite Element modeling) are seamlessly managed by NRV.

<center>
{% include _large_icon.html icon="fa-solid fa-download" href="download/" label="Download"
%}{% include _large_icon.html icon="fa-solid fa-book" href="documentation/" label="Documentation"
%}{% include _large_icon.html icon="fa-brands fa-github" href="https://github.com/nrv-framework/" label="Source code"
%}{% include _large_icon.html icon="fa-brands fa-slack" href="https://join.slack.com/t/fenicsproject/shared_invite/zt-2wa76d0xw-ecfxcPj25K8pc7q7~1AK8g" label="Slack"
%}
</center>



FEniCS is a [NumFOCUS](https://www.numfocus.org/) fiscally supported
project. If you like FEniCS and want to support our mission to produce
the best possible platform for open-source computing, consider making [a
donation](https://numfocus.org/donate-to-fenics) to our project.

[![NumFOCUS](/assets/img/numfocus.png){: .image-center }](https://www.numfocus.org/)
