# MotionPlanning
sparsRRT*
Abstract:
A motion planning algorithm for autonomous aggressive vehicle maneuvers is developed. The motion planner takes advantages of the sparse stable trees (SST), the RRT* algorithm and the model predictive control (MPC) design. The use of the sparsity property helps to reduce the computational burden of the RRT* method by removing non-useful nodes in each iteration (i.e., rewiring) and therefore to quickly converge to the optimal solution. A goal-biased input is used to achieve a fast convergence. A nonlinear MPC is used to compute and find the attracting area for the generated trajectory with consideration of constraints of the system.
