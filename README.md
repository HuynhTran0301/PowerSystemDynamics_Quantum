# Repository for Simulation of the Power System Dynamics with Quantum Computing

This repository contains the source code necessary to reproduce the results for solving differential algebraic equations in power system dynamics.

In addition, the repository includes three folders: the conference version, the journal version, and the PES General Meeting.

## NAPS Conference version

The conference version consists of code to reproduce the results presented in the paper:

Applying Quantum Computing to Simulate Power System Dynamics’ Differential-Algebraic Equations:
[10.1109/NAPS58826.2023.10318578](https://ieeexplore.ieee.org/document/10318578)

By Huynh T. T. Tran,  Hieu T. Nguyen, Long Thanh Vu and Samuel T. Ojetola.

Accepted and presented to the 55th Annual North American Power Symposium (NAPS), 2023.

In this version, we simulate the power system dynamics with the synchronous machine, IEEE type 1 exciter system, and do not model the turbine and speed governor system. The model was tested in two cases: i) single machine infinite bus system and ii) three machine nie bus system.


## IET Journal version

The conference version consists of code to reproduce the results presented in the paper:

Solving differential-algebraic equations in power system dynamic analysis with quantum computing:
[10.1049/enc2.12107](https://doi.org/10.1049/enc2.12107)

By Huynh T. T. Tran,  Hieu T. Nguyen, Long Thanh Vu and Samuel T. Ojetola.

In the journal version,  we have enhanced the conference model by integrating the turbine and speed governor systems. Building upon the two initial test cases, we have incorporated additional tests focusing on the internal node model, allowing a greater understanding of the system's dynamics.


## PES General Meeting Version

The conference version consists of code to reproduce the results presented in the paper:

Power System Dynamic Analysis Using Quantum Linear Differential Equation Solver Oracle.
[10.1109/PESGM51994.2024.10688522](https://ieeexplore.ieee.org/document/10688522)

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



