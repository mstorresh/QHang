# QHang
Hackaton Womanium


## Members
* Cristian Galvis
  * Cristian2407
  * GitHub ID: cagalvisf
  * email:     cagalvisf@unal.edu.co
* Manuel Torres
  * Discord: Manuel Sebastian Torres
  * GITHUB ID: mstorresh
  * email:     mstorresh@unal.edu.co

## Pitch Presenter

Cristian

# Quantum-approximate-optimisation-algorithms-for-real-world-scenarios---Strangeworks

## Introduction

Several of the topics that are currently emerging have problems due to the amount of computational resources that are required, from studying new DNA behaviors, to organizing sporting events or analyzing structures with new materials. All these cases have required a tremendous computational power, which classical computing has not been able to solve completely, due to the fact that the cost grows exponentially with the number of parameters that the problem has.
Therefore, one of the options to solve this problem is the Quantum approximate optimisation algorithms (QAOA). This method is reliable but has the detail that the time in Quantum Hardware is expensive, so the idea of the project is to find a way to reduce slightly the costs of this method and hope that in the future it will be smaller and more optimal than the classical models.   


## Solution

The component of the problem proposed by Strangeworks is to approach the maximum cut problem from a graph representation of the project. This problem mainly suggests working with 4 binary nodes. Using this representation, we start with the QAOA process of finding the minimum energy of the Hamiltonian. With this in mind, We would like to know the cost of doing it with the QOAO. 

The steps: 
* Define the Graph with the weights and 4 nodes
* Obtain the Hamiltonian from the graph 
* Getting the exact solution (obtain the exact ground state of the Hamiltonian)
* Initialize the parameters (the 2 angles)
  * Preparing the state with the qaoa circuit, measure and compute the expectation value.
  * Finding the new values of parameters
  * repeat the process     


## Discussion 

During the process of the analysis and solution of this project it was concluded: 




Besides that we not only stayed with the general idea of max cut with QAOA, but we found direct applications in different areas, which one that caught our attention is the application in spin glass(1), which is important in materials science. Something interesting in these cases is the existence of negative weights, which when processed by the QAOA system increased the amount of solutions and therefore the resources needed to develop this kind of problems.  
 
(1) "A spin glass is a disordered magnetic state where the spatial average of the magnetization over the sites is zero while the time average of the orientation of any given spin is non-zero, in contrast to a paramagnet where both averages are zero." Taken from: https://www.sciencedirect.com/topics/materials-science/spin-glass

