# Q-PORT: Quantum-aided Portfolio Optimization & Resource Tracker

Q-PORT aims to optimize a portfolio of scholarships using quantum computing techniques provided by Qiskit. It leverages quantum algorithms such as Variational Quantum Eigensolver (VQE) and Quantum Approximate Optimization Algorithm (QAOA) to find the optimal selection of scholarships given certain constraints.
Project Overview:

∙ Data Parsing: Scholarships data is parsed from a file, extracting relevant information like due dates and amounts.

∙ Risk and Return Calculation: Expected returns and risk factors are calculated based on the due dates and amounts of scholarships.

∙ Portfolio Optimization: The problem is framed as a portfolio optimization task, with expected returns and covariance matrix derived from the scholarship data.

∙ Quantum Optimization Algorithms:
    ○ VQE Optimization: Variational Quantum Eigensolver is employed to find the minimum eigenvalue of the problem Hamiltonian.
    ○ QAOA Optimization: Quantum Approximate Optimization Algorithm is used to solve combinatorial optimization problems by preparing an approximate ground state of a        corresponding Ising Hamiltonian.

Key Components:

∙ Qiskit Libraries:
    ○ qiskit.circuit.library.TwoLocal: An ansatz for variational circuits used in VQE.
    ○ qiskit_aer.primitives.Sampler: Sampler for executing circuits on different backends.
    ○ qiskit_algorithms: Contains various quantum algorithms like VQE, QAOA, and SamplingVQE.
    ○ qiskit_optimization.algorithms.MinimumEigenOptimizer: Utilized for solving minimum eigenvalue problems.
    
∙ Optimization Techniques:
        COBYLA Optimizer: Used for classical optimization within the quantum algorithms.
        
∙ Visualization:
        matplotlib: Utilized for plotting the covariance matrix.

Future Scope:

∙ Integration with real quantum hardware for enhanced performance.

∙ Incorporating more sophisticated optimization techniques.

∙ Scaling up to handle larger datasets efficiently.

This project demonstrates the potential of quantum computing in tackling portfolio optimization problems efficiently and provides a foundation for further research in this domain.
