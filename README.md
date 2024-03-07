# Repository for Simulation of the Power System Dynamics with Quantum Computing

This repository contains the source code necessary to reproduce the results for solving differential algebraic equations in power system dynamics.

In addition, the repository includes three folders: the conference version, the journal version, and the PES General Meeting.

## Conference version

The conference version consists of code to reproduce the results presented in the paper:

Applying Quantum Computing to Simulate Power System Dynamics’ Differential-Algebraic Equations:
[10.1109/NAPS58826.2023.10318578](https://ieeexplore.ieee.org/document/10318578)

By Huynh T. T. Tran,  Hieu T. Nguyen, Long Thanh Vu and Samuel T. Ojetola.

Accepted and presented to the 55th Annual North American Power Symposium (NAPS), 2023.

In this version, we simulate the power system dynamics with the synchronous machine, IEEE type 1 exciter system, and do not model the turbine and speed governor system. The model was tested in two cases: i) single machine infinite bus system and ii) three machine nie bus system.

### Abstract:
Power system dynamics are generally modeled by high dimensional nonlinear differential-algebraic equations due to a large number of generators, loads, and transmission lines. Thus, its computational complexity grows exponentially with the system size. This paper demonstrates the potential use of quantum computing algorithms to model the power system dynamics. Leveraging a symbolic programming framework, we equivalently convert the power system dynamics' differential-algebraic equations (DAEs) into ordinary differential equations (ODEs), where the data of the state vector can be encoded into quantum computers via amplitude encoding. The system's nonlinearity is captured by Taylor polynomial expansion, the quantum state tensor, and Hamiltonian simulation, whereas state variables can be updated by a quantum linear equation solver. Our results show that quantum computing can simulate the dynamics of the power system with high accuracy, whereas its complexity is polynomial in the logarithm of the system dimension. Our work also illustrates the use of scientific machine learning tools for implementing scientific computing concepts, e.g., Taylor expansion, DAEs/ODEs transform, and quantum computing solver, in the field of power engineering.


## Journal version

In the journal version,  we have enhanced the conference model by integrating the turbine and speed governor systems. Building upon the two initial test cases, we have incorporated additional tests focusing on the internal node model, allowing a greater understanding of the system's dynamics.


## PES General Meeting

The conference version consists of code to reproduce the results presented in the paper:

Power System Dynamic Analysis Using Quantum Linear Differential Equation Solver Oracle.

By Huynh T. T. Tran, Anh Phuong Ngo and Hieu T. Nguyen.


## Language programming:
We use Julia to implement the algorithm that is running in the Jupyter Notebook, and the results are prepared in Matlab.
To run the code, please install Julia version 1.9.2, and later, Julia will instruct you how to add the necessary packet for running the code.

## Question?
Please contact Ethan Tran at email htran@aggies.ncat.edu if you have any code or implementation questions.

# Citation

Please cite this paper if you use the code above in your work.
```
@article{tran2024solving,
  title={Solving differential-algebraic equations in power system dynamic analysis with quantum computing},
  author={Tran, Huynh TT and Nguyen, Hieu T and Vu, Long T and Ojetola, Samuel T},
  journal={Energy Conversion and Economics},
  volume={5},
  number={1},
  pages={40--53},
  year={2024},
  publisher={Wiley Online Library}
}
```



