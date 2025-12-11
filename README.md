# 🤖 Robot Path Planning with Genetic Algorithm (GA) & Bézier Curves  
### Academic Demonstration Notebook

This repository provides an academic-style implementation of **Robot Path Planning** using:

- **Genetic Algorithm (GA)** for global optimization  
- **Bézier Curves** for smooth trajectory generation  
- **CSV datasets** defining Start, Goal, and Obstacles  

The notebook `Path map.ipynb` demonstrates how evolutionary computation can be applied to autonomous navigation tasks in a clear, modular, and experiment-oriented manner.

---

## 📚 1. Overview

A **Genetic Algorithm (GA)** is a population-based optimization technique inspired by biological evolution.  
In this project, GA optimizes the control points of a **Bézier curve**, enabling a robot to travel from a Start point to a Goal point while safely avoiding obstacles.

The notebook includes:

- Reading datasets from CSV  
- GA optimization of path geometry  
- Bézier curve construction  
- Collision detection  
- Visualization of optimized trajectories  

---

## 🎯 2. Objectives

✔ Understand how GA works in robot navigation  
✔ Modify and experiment with GA parameters  
✔ Visualize Bézier-based path planning  
✔ Explore collision-aware optimization  
✔ Use this template for research or academic assignments  

---

## 🧱 3. Genetic Algorithm Workflow

### **Step 1 — Initialization**
A population of randomly generated chromosomes is created.  
Each chromosome represents Bézier control points.

### **Step 2 — Fitness Evaluation**
Each path is evaluated based on:

- Total path length  
- Penalties for collision with obstacles  
- Smoothness of curvature  

### **Step 3 — Genetic Operators**
- **Selection** → choose the strongest solutions  
- **Crossover** → mix parent chromosomes  
- **Mutation** → introduce variability  
- **Elitism** → keep the best solutions  

### **Step 4 — Bézier Curve Construction**
Control points are converted into Bézier curves that represent the robot’s trajectory.

### **Step 5 — Visualization**
Plots show:

- Start & Goal positions  
- Obstacle field  
- Final optimized Bézier path  
- GA convergence plot  

---

## 🗂 4. Dataset Description

All datasets are located in the `data/` directory.

### **map_points.csv**
Single navigation scenario:
start_x,start_y,start_z,goal_x,goal_y,goal_z
0,0,0,10,10,0


### **map_points_expanded.csv**
Multiple Start–Goal scenarios:
0,0,0,10,10,0
2,3,0,12,8,0
5,1,0,15,14,0
8,6,0,18,3,0


### **obstacles.csv**
Obstacle coordinates:
3,4,0
4,4,0
5,4,0
6,6,0
7,7,0
8,5,0


---

## 🧪 5. How to Run the Notebook

## 🧠 6. Educational Value

This project is ideal for:

- Robotics & AI students

- Evolutionary computation research

- Optimization algorithm demonstrations

- Educational labs and assignments

## 🧩 7. Possible Extensions

- Support for 3D navigation

- Dynamic obstacle generation

- Map extraction from images

- Multi-agent path planning

- Hybrid GA + Reinforcement Learning

## 📄 8. License

This project is distributed under the MIT License.

## ⭐ 9. Support

If you find this repository useful, please star ⭐ it on GitHub.
