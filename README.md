# Entanglement Purification: The BBPSSW Protocol
***

In this tutorial we demonstrate the use of IBM Qiskit and the IBM Q Experience by implementing a protocol for entanglement purification, the BBPSSW protocol. This technique from quantum information processing, which is especially required for quantum communication, allows to generate highly-entangled qubit pairs from noisy sources. In the protocol presented here, we will use two entangled qubit pairs to increase the fidelity of one of the pairs with respect to a maximally-entangled Bell state.

After a brief introduction to the topic itself, we will give a detailed description of how to implement the entanglement purification protocol in Qiskit. We then proceed systematically and simulate the created quantum circuits first with Qiskit’s integrated simulator for a perfect quantum system, then include noise in the simulation and finally run the protocol on a real IBM Q device using the IBM Q Experience.

## Contents

* **Part I: Introduction to Entanglement Purification and the BBPSSW Protocol**
  
  
* **Part II: Implementation of Quantum Circuit for BBPSSW Protocol in Qiskit**
  
  
* **Part III: Simulation of the BBPSSW Protocol using Qiskit**


* **Part IV: Including Noise in the Simulation Model**


* **Part V: Entanglement Purification on a Real IBM Q Device**


* **Part VI: Conclusion and Further Ideas**

## Learning Objectives

We give a comprehensive explanation of the following basic features of Qiskit and the IBM Q Experience:

* Composition of quantum circuits from single- and two-qubit gates
* Generation of parametrized quantum circuits
* Implementation of qubit measurements
* Execution of quantum circuits using the simulator integrated in Qiskit
* Execution of quantum circuits on real IBM Q devices using the IBM Q Experience
* Extraction of measurement results

In addition, we explain more advanced uses of Qiskit and the topics are:

* Performance of quantum state tomography
* Postprocession of measurement results for conditional quantum state tomography
* Extraction of noise parameters from real devices using the IBM Q Experience
* Creation of simple noise models
* Simulation of noisy systems using Qiskit's integrated simulator
* Calculation of an ensemble average over many quantum systems

We also give an introduction to entanglement purification and explain the associated quantum protocol, which we will implement step by step in Qiskit. However, our main focus is on the use of Qiskit and we refer readers interested in in-depth explanations of entanglement purification to the references we provide.


## Prior Knowledge

To understand the tutorial, the following topics from the field of quantum information theory are required:

* Common single- and two-qubit gates
* Qubit entanglement or the notion of maximal entanglement
* Bell states
* Mixed quantum states and density matrices
* Quantum state fidelity

The following topics are helpful, but not absolutely necessary, to work through this tutorial:

* Quantum state tomography

Since this tutorial is provided as Jupyter notebook, basic knowledge of the following Python libraries is recommended:

* NumPy
