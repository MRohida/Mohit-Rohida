---
title: "Quantum algorithm for edge detection in digital grayscale images"
collection: publications
category: preprints
permalink: /publication/edge-detection
excerpt: 'In this work, we propose a novel quantum algorithm for edge detection in digital grayscale images, based on the sequency-ordered Walsh-Hadamard transform. The proposed method significantly improves upon existing quantum techniques for edge detection by using a quantum algorithm for the sequency-ordered Walsh-Hadamard transform, achieving a circuit depth of $$ O(n) $$ (where $$ n $$  is the number of qubits). [Read more...](https://mrohida.github.io/Mohit-Rohida//publication/edge-detection)'
date: 2025-07-10
venue: 'arXiv'
citation: 'M. Rohida, A. Shukla, and P. Vedula, Quantum algorithm for edge detection in digital grayscale
images, 2025. <i>arXiv</i>: 2507.06642 [quant-ph].'
paperurl: 'https://arxiv.org/abs/2507.06642'
---
In this work, we propose a novel quantum algorithm for edge detection in digital grayscale images, based on the sequency-ordered Walsh-Hadamard transform. The proposed method significantly improves upon existing quantum techniques for edge detection by using a quantum algorithm for the sequency-ordered Walsh-Hadamard transform, achieving a circuit depth of $$ O(n) $$ (where $$ n $$ is the number of qubits). This represents a notable enhancement over the Quantum Fourier Transform (QFT), which has a circuit depth of $$ O(n^2) $$. Furthermore, our approach for edge detection has a computational cost $$ O(\text{log}_2(N_1 N_2)) $$ (both gate complexity and quantum circuit depth) of  for an image of size $$ N_1\times N_2 $$, offering a considerable improvement over the Quantum Hadamard Edge Detection (QHED) algorithm, which incurs a cost of $$ O(\text{poly}(\text{log}_2(N_1 N_2))) $$. By integrating a quantum high-pass filter with the sequency-ordered Walsh-Hadamard transform, the algorithm effectively extracts edge information from images. Computational examples are provided to demonstrate the efficacy of the proposed algorithm which provides a better performance in comparison to QHED.
