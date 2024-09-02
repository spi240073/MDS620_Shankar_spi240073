#Answer 1
By simulating the environment with probabilistic state transitions and rewards, MDPs manage uncertainty. The goal of decision-making is to maximize predicted rewards over the long term.
While deterministic models simplify decision-making processes by assuming predictable outcomes devoid of variability, they are unable to account for uncertainty or stochastic settings in their modeling and planning.
Deterministic models are applicable in situations where outcomes are known and predictable, but mixed-effects models (MDPs) are more suited for real-world problems when outcomes are unknown, and actions have probabilistic impacts.

#Answer 2
High R-squared (almost 1): The agent prioritizes long-term gains and thorough preparation, placing nearly equal weight on future rewards as on present ones.
Low 𝛾γ (around 0): The agent is primarily concerned with obtaining rewards right away and makes actions that have minimal bearing on how things will turn out down the road.
When 𝛾 = 0 γ = 0, the agent makes no allowances for future benefits and solely thinks about the present.
The agent assumes an unlimited horizon, values all future benefits equally, and concentrates on the total long-term payoff (𝛾 = 1 γ = 1).
The selection of 𝛾γ ought to be in harmony with the particular objectives and attributes of the issue domain. A larger 𝛾γ is suitable for environments with a lot of long-term dependencies, whereas a lower 𝛾γ might be recommended for issues where quick fixes are essential.

#Answer 3
An MDP's activities and statuses are assessed using value functions. The action value function Q(s,a) measures the expected reward of taking an action from a state under a policy, whereas the state value function V(s) measures the expected reward from a state under a policy.
The best predicted rewards are ascertained with the aid of optimal value functions, which also direct the formulation of ideal policies.
In order to compute these functions, the Bellman equations must be solved. This is done by using iterative techniques or algorithms like value iteration and Q-learning, which update value estimations in a systematic manner in order to identify the best solutions.
Value functions play a vital role in the development and evaluation of policies within MDPs, directing agents towards choices that optimize their anticipated benefits in the long run.

#Answer 4

Different states have varying inventory levels.
The quantities of inventory to be ordered are actions.
The profit or penalty linked to various inventory levels and decision-making results are called rewards.
Transition probabilities explain how decisions about ordering and demand affect inventory levels.
Given the stochastic nature of demand, MDPs aid in the determination of the best ordering strategy by weighing the potential profits from sales against the costs of overstock and stockouts. The store can create a policy that maximizes predicted profit over time and ensures effective inventory management by solving the MDP.

#Section B

Value Function after 1 iterations:
[[ -1. -1. -1. -1.]
[ -1. -10. -1. -1.]
[ -1. -1. -10. 8.]
[ -1. -1. 8. 10.]]

Value Function after 2 iterations:
[[ -1.9 -1.9 -1.9 -1.9]
[ -1.9 -10. -1.9 6.2]
[ -1.9 -1.9 -10. 8. ]
[ -1.9 6.2 8. 10. ]]

Value Function after 3 iterations:
[[ -2.71 -2.71 -2.71 4.58]
[ -2.71 -10. 4.58 6.2 ]
[ -2.71 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Value Function after 4 iterations:
[[ -3.439 -3.439 3.122 4.58 ]
[ -3.439 -10. 4.58 6.2 ]
[ 3.122 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Value Function after 5 iterations:
[[ -4.0951 1.8098 3.122 4.58 ]
[ 1.8098 -10. 4.58 6.2 ]
[ 3.122 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Value Function after 6 iterations:
[[ 0.62882 1.8098 3.122 4.58 ]
[ 1.8098 -10. 4.58 6.2 ]
[ 3.122 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Value Function after 7 iterations:
[[ 0.62882 1.8098 3.122 4.58 ]
[ 1.8098 -10. 4.58 6.2 ]
[ 3.122 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Total Iterations until Convergence: 7

Final Optimal Value Function:
[[ 0.62882 1.8098 3.122 4.58 ]
[ 1.8098 -10. 4.58 6.2 ]
[ 3.122 4.58 -10. 8. ]
[ 4.58 6.2 8. 10. ]]

Optimal Policy:
[['D' 'R' 'D' 'D']
['D' ' ' 'R' 'D']
['D' 'D' ' ' 'D']
['R' 'R' 'R' ' ']]
