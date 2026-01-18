Value Iteration on FrozenLake (Gymnasium)
Objective

The goal of this assignment is to understand and implement Value Iteration, a core dynamic programming algorithm used to solve Markov Decision Processes (MDPs).

In this project, Value Iteration is applied to the FrozenLake-v1 environment from Gymnasium to find an optimal policy that maximizes the expected reward.

Background

Value Iteration is a simple yet powerful algorithm that combines:

Policy Evaluation – estimating how good a state is

Policy Improvement – choosing better actions based on those estimates

Instead of performing these as separate steps, Value Iteration updates the value function directly until it converges to the optimal value function.

 Approach

Initialize the value function for all states.

Iteratively update the value of each state using the Bellman optimality equation.

Continue updates until the value function converges.

Derive the optimal policy from the final value function.

Outcome

An optimal value function for the FrozenLake environment

An optimal policy that maximizes the expected reward

Environment Used

Gymnasium

FrozenLake-v1

Key Concepts

Markov Decision Process (MDP)

Value Iteration

Dynamic Programming

Optimal Policy

Bellman Optimality Equation
