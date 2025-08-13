#  Reinforcement Learning Specialization – University of Alberta (Coursera)

A collection of assignment solutions (Jupyter Notebooks and Python scripts) for the **Reinforcement Learning Specialization**, taught by the University of Alberta and offered through Coursera.


##  About the Specialization 

The **Reinforcement Learning Specialization** is a four-course series that covers fundamental to advanced concepts in reinforcement learning (RL). Learners explore how to build decision-making agents through hands-on programming exercises and quizzes. The specialization encompasses:

1. **Fundamentals of Reinforcement Learning** — Formalize control problems as Markov Decision Processes (MDPs), understand exploration–exploitation tradeoffs, and apply dynamic programming techniques.

2. **Sample-based Learning Methods** — Dive into Monte Carlo methods, Temporal-Difference (TD) learning, and model-based approaches like Dyna in the absence of a full model.

3. **Prediction & Control with Function Approximation** — Apply function approximation via tile-coding and neural networks; implement actor-critic and policy gradient methods.

4. **Capstone: A Complete Reinforcement Learning System** — Integrate previous knowledge to develop a complete RL agent, including MDP formulation, algorithm selection, and empirical studies in environments like Lunar Lander.

Upon completion, learners gain practical and theoretical grounding in building RL systems, understanding a wide range of algorithms—from TD and Monte Carlo methods to policy gradients, as well as expertise in formulating RL problems.



##  Repository Overview

```

Reinforcement-Learning-Specialization/
│
├── Fundamentals/                     # Assignments for Course 1
│   ├── bandits.ipynb
│   ├── dynamic\_programming.ipynb
│   └── ...
│
├── Sample-based Methods/             # Course 2 assignments
│   ├── mc\_control.ipynb
│   ├── td\_prediction.ipynb
│   ├── q\_learning\_expected\_sarsa.ipynb
│   └── dyna\_q\_experiments.ipynb
│
├── Function Approximation/           # Course 3 assignments
│   ├── semi\_gradient\_td.ipynb
│   ├── neural\_network\_td.ipynb
│   ├── sarsa\_tile\_coding.ipynb
│   └── actor\_critic\_tile\_coding.ipynb
│
├── Capstone/                         # Course 4 capstone project
│   ├── mdp\_formulation.ipynb
│   ├── lunar\_lander\_agent.ipynb
│   └── parameter\_study.ipynb
│
├── requirements.txt                  # Python dependencies
└── README.md                         # Project documentation

````


##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ai-art-dev99/reinforcement-learning-specialization.git
cd reinforcement-learning-specialization
````

### 2. Install Dependencies

```bash
python3 -m venv env
source env/bin/activate             # Windows: env\Scripts\activate
pip install -r requirements.txt
```

### 3. Explore Notebooks

Open any of the `*.ipynb` files (e.g., `bandits.ipynb`) using Jupyter or VS Code. Each notebook is structured to:

* Define the RL problem environment
* Implement the algorithm
* Visualize or print performance metrics
* Reflect upon outcomes and key observations


## Learning Outcomes & Topics

* **MDP Formalization** (states, actions, transitions, rewards)
* **Exploration Strategies**: ε-greedy, UCB, optimistic initial values
* **Dynamic Programming**: Policy evaluation, policy iteration, value iteration
* **Sample-based Methods**: Monte Carlo, TD(0), SARSA, Q-learning, Expected SARSA, Dyna-Q
* **Function Approximation**: Tile-coding, semi-gradient TD, neural networks
* **Policy Gradient Methods**: Actor-Critic with tile-coding
* **Capstone Integration**: Lunar Lander control agent, parameter tuning, empirical verification


## Acknowledgements

* University of Alberta and the Alberta Machine Intelligence Institute for the specialization content [Coursera Blog]([https://blog.coursera.org/university-of-alberta-reinforcement-learning-new-specialization])
* Coursera’s platform for delivering the specialization [Coursera Blog]([https://blog.coursera.org/university-of-alberta-reinforcement-learning-new-specialization])
* Sutton and Barto’s foundational textbook *Reinforcement Learning: An Introduction* referenced throughout [Medium]([https://medium.com/%40cyril_anderson/review-coursera-reinforcement-learning-specialization-13df003a6df3])


## License

This repository is released under the **MIT License**.


*Developed during the Reinforcement Learning Specialization*
