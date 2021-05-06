This set of notebooks contains the material for a comprehensive 54-hour course on **open quantum systems** (OQS), starting from basic concepts and covering the most essential concepts in the literature of OQS. Moreover, we present a novel idea: to teach how to simulate many paradigmatic examples of OQS dynamics with [Qiskit](https://qiskit.org) and the [IBM Q Experience](https://quantum-computing.ibm.com) processors. This idea finds its origin in a recent publication ([García-Pêrez, Rossi, Maniscalco, NPJ Quantum Inform. 6, 1 (2020)](https://www.nature.com/articles/s41534-019-0235-y)), in which we demonstrate that the IBM Q Experience is a versatile and robust platform for simulating open quantum systems.

The course is aimed at master students with a background in Quantum Mechanics and Quantum Information theory who are also familiar with Qiskit. It is divided into lectures and projects. Through the lecture notes, the lecturer will find several examples of important concepts for OQS in terms of circuits, with which we assume the student to be acquainted, as well as *interactive plots* illustrating OQS dynamics. The lecture material also includes many circuits that enable the simulation of OQS dynamics on the real IBM Q devices, with comprehensive explanations on their working principles. Finally, the lectures are to be supplemented with *guided practical "hands-on" sessions* (found in the *Projects* section) in which the students must implement the corresponding circuits and analyze the results.

![](images/oqs.001.png)

# Table of contents

## Lectures

1. [Introduction](introduction.md)
2. [Preliminaries](preliminaries.ipynb)
3. [Microscopic derivation of the master equation](microscopic_derivation_of_the_markovian_master_equation.ipynb)
4. [Dynamical maps: Markovian semigroups](markovian_semigroups.ipynb)
5. [Dynamical maps: divisibility](divisible_maps.ipynb)
6. [Projection operator techniques](projection_operator_techniques.ipynb)
7. [Jaynes-Cummings model with losses](jaynes_cummings_with_losses.ipynb)
8. [Non-Markovian quantum dynamics](non-markovian_quantum_dynamics.ipynb)

## Projects

1. [Depolarizing channel](project_1-depolarizing_channel.ipynb) ([Solution](project_1-solution.ipynb))
2. [Pauli channel](project_2-pauli_channel.ipynb) ([Solution](project_2-solution.ipynb))
3. [Markovian reservoir engineering](project_3-reservoir-engineering.ipynb) ([Solution](project_3-solution.ipynb))
3. [Amplitude damping channel](project_4-amplitude_damping.ipynb) ([Solution](project_4-solution.ipynb))