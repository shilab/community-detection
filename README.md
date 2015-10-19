# community-detection
A Graph Community Approach for Constructing microRNA Networks

We used igraph to employ the spin glass community detection algorithm, which is primarily based on thermodynamics. The model is based on a optimizing the qualifying energy function, known as the Hamiltonian, in Equation such that it minimizes the energy and maximizes the modularity of the system. Compared with other methods that optimize modularity solely, the spin glass algorithm finds the spin configuration (the community indices) that minimizes the Hamiltonian. To minimize the Hamiltonian, this particular algorithm uses simulated annealing for optimization.
