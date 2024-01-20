# Repository for Solving Differential-Algebraic Equations in Power System Dynamic Analysis with Quantum Computing

This repository contains the source code necessary to reproduce the results for solving differential algebraic equations in power system dynamics.

In addition, the repository includes two folders: the conference version and the journal version.

## Conference version

The conference version consists of code to reproduce the results presented in the paper:

Applying Quantum Computing to Simulate Power System Dynamics’ Differential-Algebraic Equations:
[10.1109/NAPS58826.2023.10318578](https://ieeexplore.ieee.org/document/10318578)

By Huynh T. T. Tran,  Hieu T. Nguyen, Long Thanh Vu and Samuel T. Ojetola.

Accepted and presented to the 55th Annual North American Power Symposium (NAPS), 2023.

In this version, we simulate the power system dynamics with the synchronous machine, IEEE type 1 exciter system, and do not model the turbine and speed governor system. The model was tested in two cases: i) single machine infinite bus system and ii) three machine nie bus system.

### Abstract:
Power system dynamics are generally modeled by high dimensional nonlinear differential-algebraic equations due to a large number of generators, loads, and transmission lines. Thus, its computational complexity grows exponentially with the system size. This paper demonstrates the potential use of quantum computing algorithms to model the power system dynamics. Leveraging a symbolic programming framework, we equivalently convert the power system dynamics' differential-algebraic equations (DAEs) into ordinary differential equations (ODEs), where the data of the state vector can be encoded into quantum computers via amplitude encoding. The system's nonlinearity is captured by Taylor polynomial expansion, the quantum state tensor, and Hamiltonian simulation, whereas state variables can be updated by a quantum linear equation solver. Our results show that quantum computing can simulate the dynamics of the power system with high accuracy, whereas its complexity is polynomial in the logarithm of the system dimension. Our work also illustrates the use of scientific machine learning tools for implementing scientific computing concepts, e.g., Taylor expansion, DAEs/ODEs transform, and quantum computing solver, in the field of power engineering.

### Numerical Results:
#### Single machine infinite bus system:

![one machine](https://github.com/ThanhEthan/PowerSystemDynamics_Quantum/assets/115194407/8e5932cf-303e-45d4-b11a-87e63e921b2a)

#### Three machine infinite bus system:

![three machine](https://github.com/ThanhEthan/PowerSystemDynamics_Quantum/assets/115194407/a368940a-2a71-4da2-bfad-c66953fec44c)

## Journal version

In the journal version,  we have enhanced the conference model by integrating the turbine and speed governor systems. Building upon the two initial test cases, we have incorporated additional tests focusing on the internal node model, allowing a greater understanding of the system's dynamics.

### Several Numerical Results:
#### Single machine infinite bus system:

![one machine](https://github.com/ThanhEthan/PowerSystemDynamics_Quantum/assets/115194407/cbd9c429-f3c3-46d5-b9d6-d660f7b4e045)


#### Internal node model (Three machine nine bus system):

![internal](https://github.com/ThanhEthan/PowerSystemDynamics_Quantum/assets/115194407/a55a002e-5442-429d-afbf-63352a47b465)


#### General DAEs (Three machine nine bus system):

![three machine](https://github.com/ThanhEthan/PowerSystemDynamics_Quantum/assets/115194407/cdf2a7ab-5aac-419a-9aa9-a1453d093f96)


## Language programming:
We use Julia to implement the algorithm that is running in the Jupyter Notebook, and the results are prepared in Matlab.
To run the code, please install Julia version 1.9.2, and later, Julia will instruct you how to add the necessary packet for running the code.

## Question?
Please contact Ethan Tran at email htran@aggies.ncat.edu if you have any code or implementation questions.

# Citation

Please cite this paper if you use the code above in your work.
```
@inproceedings{tran2023applying,
  title={Applying Quantum Computing to Simulate Power System Dynamics' Differential-Algebraic Equations},
  author={Tran, Huynh TT and Nguyen, Hieu T and Vu, Long Thanh and Ojetola, Samuel T},
  booktitle={2023 North American Power Symposium (NAPS)},
  pages={1--6},
  year={2023},
  organization={IEEE}
}
```



