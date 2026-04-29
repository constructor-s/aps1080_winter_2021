# Reinforcement Learning Portfolio

A comprehensive collection of reinforcement learning implementations and exercises from APS1080 (Winter 2021), covering fundamental algorithms, environments, and deep learning techniques in autonomous decision-making systems.

## Overview

This course provided hands-on experience with core reinforcement learning concepts, from foundational Markov Decision Processes to advanced deep learning function approximation. The projects progress through classical tabular methods, temporal difference learning, and neural network-based control, demonstrating both theoretical understanding and practical implementation skills.

---

## 📚 Course Assignments (A1-A4)

Progressive implementation of RL algorithms with increasing complexity:

### **A1: Foundations - Markov Decision Processes** 
**Environment:** FrozenLake (4×4 gridworld)
- MDP fundamentals: state spaces, action spaces, reward structures
- Environment dynamics: p(s',r|s,a) transition probabilities
- Discrete, deterministic environment interaction
- Foundation for understanding all subsequent RL concepts

### **A2: Monte Carlo Control Methods**
- **Core Concepts:** Policy evaluation, policy improvement, exploring starts
- ε-soft policies for balancing exploration-exploitation
- On-policy vs. off-policy learning distinctions
- Model-free control via episode sampling and return averaging
- Practical understanding of episodic task learning

### **A3: Temporal Difference Methods - TD(n) Learning**
**Environment:** MountainCar (continuous state space: position, velocity)
- TD(n) bootstrapping and value function estimation
- Introduction to function approximation for continuous states
- State discretization techniques
- Extending tabular methods beyond discrete state spaces

### **A4: Function Approximation & Deep Reinforcement Learning**
**Environments:** CartPole / MountainCar (student choice)
- **Key Innovation:** Replacing tabular value functions with neural networks
- Neural network function approximation with PyTorch
- SARSA(n) with deep learning for continuous control
- Stochastic gradient descent for value function training
- Scalable RL for high-dimensional state spaces

---

## 🧪 Exercises (E0-E4)

Targeted practical exercises reinforcing theoretical concepts:

### **E0: Foundational AI & Control**
**Application:** Tic-Tac-Toe game implementation
- Board state management and game logic
- Basic AI decision-making strategies
- Foundation for autonomous system design

### **E1: RL Theory Foundations** (Sutton & Barto, Chapter 3)
**Application:** Tic-Tac-Toe learning player
- **Key Concepts:** Returns G_t, value functions V(s), action-value functions Q(s,a)
- Bellman equations and value relationships
- Exploration vs. exploitation trade-offs
- Mathematical foundations combined with practical game implementation

### **E2: Monte Carlo on Continuous Environments**
**Environment:** CartPole (4 continuous observations: position, velocity, pole angle, angular velocity)
- Applying Monte Carlo to continuous-state problems
- State discretization for continuous control
- On-policy MC control with ε-soft policies
- CartPole mechanics and OpenAI Gym library familiarity

### **E3: Temporal Difference Control Algorithms**
**Environment:** CartPole with state discretization
- **Algorithm Comparison:** SARSA (on-policy), Q-Learning (off-policy), Expected SARSA (off-policy)
- TD(0) vs. MC vs. DP trade-offs
- Implementation and empirical analysis of three fundamental control methods

### **E4: Neural Network Function Approximation**
- **E4.ipynb:** PyTorch fundamentals for RL
  - Neural network architecture design
  - Gradient computation and backpropagation
  - Stochastic gradient descent optimization
  - Practical training mechanics for value function approximation
  
- **E4_MountainCar.ipynb:** Real-world application to MountainCar
  - Applying learned neural network techniques to continuous control
  - Function approximation beyond CartPole

---

## 🎯 Key Algorithms & Techniques Covered

| Category | Algorithms | Environments |
|----------|-----------|--------------|
| **Tabular Methods** | Monte Carlo Control, SARSA, Q-Learning, Expected SARSA | FrozenLake, CartPole, MountainCar |
| **Temporal Difference Learning** | TD(n), SARSA(n), Q-Learning, ε-soft policies | CartPole, MountainCar |
| **Function Approximation** | Neural Networks, Deep Q-Learning with PyTorch | CartPole, MountainCar |
| **Supporting Concepts** | Bellman equations, Policy evaluation, Value iteration, State discretization | All environments |

---

## 💡 Learning Progression

1. **Fundamentals** (A1, E0, E1): MDP structure, basic game logic, foundational value functions
2. **Model-Free Control** (A2, E2): Monte Carlo methods for discrete and continuous states
3. **Temporal Difference Methods** (A3, E3): Bootstrapping, algorithm comparison, continuous control
4. **Deep Reinforcement Learning** (A4, E4): Neural networks, scalable function approximation

---

## 📊 Notable Implementations

- **Policy Evaluation & Improvement:** Implementation of full policy iteration cycles
- **State Discretization:** Techniques for handling continuous state spaces in tabular methods
- **On-Policy vs. Off-Policy:** Practical comparison through multiple algorithms
- **Deep Learning Integration:** Seamless integration of PyTorch neural networks into RL pipelines
- **Environment Interaction:** Practical work with OpenAI Gym environments
- **Exploration Strategies:** ε-soft policies, exploring starts, and comparison of exploration-exploitation methods

---

## 🛠️ Technical Stack

- **Languages:** Python
- **Core Libraries:** NumPy, OpenAI Gym, PyTorch
- **Environments:** FrozenLake, CartPole, MountainCar
- **Format:** Jupyter Notebooks with detailed explanations and implementations

---

## 📝 Course Context

**Course:** APS1080 - Reinforcement Learning (Winter 2021)  
**Institution:** University of Toronto  
**Focus:** From foundational MDP theory to practical deep RL implementations

This portfolio demonstrates both theoretical depth and practical implementation skills across the full spectrum of modern reinforcement learning approaches.
