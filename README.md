# Applying Quantum Computing to Simulate Power System Dynamics' Differential-Algebraic Equations
Power system dynamics are generally modeled by high dimensional nonlinear differential-algebraic equations due to a large number of generators, loads, and transmission lines. 
Thus, its computational complexity grows exponentially with the system size. 
This paper demonstrates the potential use of quantum computing algorithms to model the power system dynamics.
Leveraging a symbolic programming framework, we equivalently convert the power system dynamics' differential-algebraic equations (DAEs) into ordinary differential equations (ODEs), where the data of the state vector can be encoded into quantum computers via amplitude encoding.
The system's nonlinearity is captured by Taylor polynomial expansion, the quantum state tensor, and Hamiltonian simulation, whereas state variables can be updated by a quantum linear equation solver. 
Our results show that quantum computing can simulate the dynamics of the power system with high accuracy, whereas its complexity is polynomial in the logarithm of the system dimension.
Our work also illustrates the use of scientific machine learning tools for implementing scientific computing concepts, e.g., Taylor expansion, DAEs/ODEs transform, and quantum computing solver, in the field of power engineering.

# Citation
