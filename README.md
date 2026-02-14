Value Iteration on FrozenLake (Gymnasium)
Objective

The goal of this project is to understand and implement Value Iteration, a fundamental dynamic programming algorithm used to solve Markov Decision Processes (MDPs).

In this implementation, Value Iteration is applied to the FrozenLake-v1 environment from Gymnasium to compute an optimal policy that maximizes the expected cumulative reward.

📖 Background

Value Iteration is a powerful algorithm that combines:

Policy Evaluation – Estimating how good each state is (state-value function)

Policy Improvement – Selecting actions that maximize expected future rewards

Unlike traditional Policy Iteration, which performs evaluation and improvement in separate steps, Value Iteration updates the value function directly using the Bellman Optimality Equation until convergence.

The algorithm guarantees convergence to the optimal value function for finite MDPs.

🛠️ Approach

The implementation follows these steps:

Initialize the Value Function
Assign an initial value (typically zeros) to all states.

Convergence Check
Repeat updates until the maximum change in the value function is below a predefined threshold (ε).

Policy Extraction
Derive the optimal policy by selecting the action that maximizes the expected return for each state.

Outcome

Optimal Value Function for the FrozenLake environment

Optimal Policy that maximizes expected reward

Better understanding of dynamic programming methods in Reinforcement Learning

Environment

Library: Gymnasium

Environment: FrozenLake-v1

State Space: Discrete

Action Space: Discrete

Type: Stochastic Gridworld

How to Run
pip install gymnasium


Then run:

python value_iteration.py

Concepts Covered

Markov Decision Processes (MDPs)

Bellman Optimality Equation

Dynamic Programming

Value Iteration

Policy Extraction

Convergence Criteria
