The goal of this assignment is to help you understand and implement Value Iteration, a core algorithm
in dynamic programming for solving Markov Decision Processes (MDPs). You will apply Value Iteration
to the FrozenLake-v1 environment in Gymnasium to find the optimal policy that maximizes the
expected reward.
Value Iteration is a simple algorithm that combines both the Policy Evaluation and Policy Improvement
steps. It iteratively updates the value function for each state until it converges to the optimal value
function, then the policy can be derived from the value function.
