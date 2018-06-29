# VAEEntanglement
This repository contains code which explores the question, can an algorithm learn to distinguish quantum states which are known to be distinct in the way they are entangled? For those in a hurry, the answer for 3 qubits is maybe, but this approach should fail in general. My limited understanding is that entanglement witnesses are generically hard, and for mixed states, the problem is NP-hard [1](https://dl.acm.org/citation.cfm?doid=780542.780545). However, it was a fun exercise to teach myself about variational autoencoders.

This work was the result of collaboration between a group of ML-interested physicists at the University of Maryland, Zach Eldredge, who led an [effort](https://github.com/zeldredge/py-nqs) to reproduce code from 10.1126/science.aag2302, and Alireza Seif, who recently posted a [paper](https://arxiv.org/abs/1804.07718) using neural networks to improve experimental detection.

I also using [QuTip](http://qutip.org/index.html), a fantastic simulation tool, to simulate the quantum dynamics and [Tensorflow](https://www.tensorflow.org/) for the machine learning part.
