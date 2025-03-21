# Task Planning Algorithms

This repository provides a comprehensive list and categorization of various motion planning algorithms used in robotics and autonomous systems. These algorithms are crucial for enabling robots to navigate, avoid obstacles, and reach their goals efficiently in different environments.

## 📋 Categories of Task planning algorithms

The algorithms are organized into six main categories based on their core approach:

### 1️⃣ **Graph-Based Planning Algorithms**
These algorithms rely on graph traversal techniques to find optimal paths in a structured environment.

- **A* (A-Star) Algorithm** – Finds the shortest path using a heuristic function.
- **Dijkstra's Algorithm** – Similar to A*, but without a heuristic function.
- **D* (Dynamic A*)** – Adapts to changes in the environment in real-time.
- **D* Lite** – A simplified and more efficient version of D*.
- **Theta*** – An extension of A* that considers straight-line paths.
- **Bidirectional A*** – A variation of A* that searches from both start and goal nodes simultaneously.
- **Anytime Repairing A*** – Provides a suboptimal solution quickly and refines it over time.
- **Learning Real-time A*** (LRTA*) – Designed for unknown environments with real-time constraints.
- **Real-time Adaptive A*** (RTAA*) – An adaptive version of LRTA* that improves with repeated use.
- **Lifelong Planning A*** (LPA*) – Efficient for environments that change over time.
- **Hybrid A*** (HA*) – Combines A* with continuous motion primitives for smoother paths.
- **DFS/BFS (Depth-First Search / Breadth-First Search)** – Basic graph traversal algorithms.

### 2️⃣ **Sampling-Based Planning Algorithms**
These algorithms explore high-dimensional spaces by randomly sampling points and connecting them to build a feasible path.

- **RRT (Rapidly-Exploring Random Tree)** – Efficiently explores large spaces by incrementally building a tree.
- **RRT-Connect** – A bidirectional version of RRT that grows two trees and connects them.
- **Bi-RRT** – Similar to RRT-Connect but focuses on optimizing the connection process.
- **Extended-RRT** – An enhanced version of RRT with additional constraints.
- **Dynamic-RRT** – Adapts to dynamic environments in real-time.
- **RRT*** – An optimized version of RRT that guarantees asymptotic optimality.
- **Informed RRT*** – Focuses the sampling process in a more efficient way.
- **RRT* Smart** – A faster variant of RRT* with improved path optimization.
- **Anytime RRT*** – Quickly finds a suboptimal path and refines it over time.
- **Closed-Loop RRT*** – Incorporates feedback control for better trajectory execution.
- **Spline-RRT*** – Uses splines for smoother paths.
- **Fast Marching Trees (FMT*)** – Similar to RRT* but constructs a roadmap rather than a tree.
- **Batch Informed Trees (BIT*)** – Combines features of RRT* and FMT* for efficient batch processing.
- **PRM (Probabilistic Roadmap Method)** – Builds a roadmap by randomly sampling points in the environment.
- **Lazy PRM** – Delays collision checking until necessary.
- **PRM-RRT** – A hybrid method that combines PRM and RRT to handle both known and unknown areas.

### 3️⃣ **Optimization-Based Planning Algorithms**
These algorithms optimize a path based on specific criteria such as smoothness or energy efficiency.

- **CHOMP (Covariant Hamiltonian Optimization for Motion Planning)** – Uses gradient-based optimization to refine paths.
- **STOMP (Stochastic Trajectory Optimization for Motion Planning)** – Uses stochastic optimization to handle non-differentiable constraints.
- **Trajectory Optimization (TO)** – Minimizes a cost function to find an optimal trajectory.
- **Model Predictive Control (MPC)** – Predicts future states and optimizes control inputs in real-time.
- **LQR (Linear Quadratic Regulator)** – A control-theoretic approach to optimize control inputs.

### 4️⃣ **Learning-Based Planning Algorithms**
These algorithms leverage machine learning to improve motion planning, especially in complex and dynamic environments.

- **Deep Q-Network (DQN)** – Uses reinforcement learning to learn optimal paths.
- **Graph Neural Networks (GNN)** – Applies deep learning to graph-based motion planning problems.
- **Policy Gradient Methods** – Directly optimizes policies for motion planning tasks.
- **Generative Adversarial Networks (GANs)** – Can be used to generate realistic and diverse paths.

### 5️⃣ **Reactive Planning Algorithms**
These algorithms react to dynamic changes in the environment in real-time.

- **Dynamic Window Approach (DWA)** – Computes the best velocity commands to avoid obstacles in real-time.
- **Potential Fields** – Uses virtual forces to guide the robot around obstacles.
- **Vector Field Histogram (VFH)** – An improved version of potential fields that handles local minima issues.

### 6️⃣ **Motion Primitive-Based Planning Algorithms**
These algorithms use precomputed motion primitives to simplify the planning process.

- **Dynamic Movement Primitives (DMP)** – Generates adaptable and reusable motion trajectories.


