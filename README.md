# travelling-sales-man-problem

Using a GA to find a solution to the traveling salesman problem (TSP).

Problem Statement:

“Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city”

Genetic Algorithm:

Genetic algorithm is started with a set of solutions (represented by chromosomes) called population. Solutions from one population are taken and used to form a new population.The new population will be better than the old one. Solutions which are selected to form new solutions (offspring) are selected according to their fitness, the more suitable they are the more chances they have to reproduce. This is repeated until some condition for example number of populations or improvement of the best solution is satisfied. Genetic Algorithm is a paradigm that has proved to be a unique approach for solving various mathematical problems which other gradient type of mathematical optimizers have failed to reach,Ant colony optimization has been applied successfully to a large number of difficult combinatorial optimization problems.

# 🧬 Genetic Algorithm for the Traveling Salesman Problem (TSP)

This project demonstrates how to solve the classic **Traveling Salesman Problem (TSP)** using a **Genetic Algorithm (GA)** — all implemented **from scratch** in Python using **Google Colab**.

> **Built & Tested in**: [Google Colab](https://colab.research.google.com/)

---

## 📌 Project Overview

The **Traveling Salesman Problem** asks:  
> "What is the shortest possible route that visits each city exactly once and returns to the origin city?"

This project applies a **Genetic Algorithm** — inspired by natural selection — to evolve better and better solutions (routes) over time.

---

## 🔄 How the Genetic Algorithm Works

- **Chromosomes** = routes (ordered lists of cities)
- **Population** = collection of such routes
- **Fitness Function** = inverse of total route distance
- **Selection** = tournament selection to choose parents
- **Crossover** = Order Crossover (OX) to combine parents
- **Mutation** = swap two cities in a route
- **Elitism** = optional, retain best route across generations

---

## 🧪 Run the Notebook on Google Colab

You can run the project in Google Colab using the link below:

👉 **[Open in Google Colab](https://colab.research.google.com/drive/1pwSorjICCiaQtKQ92-DOGydCoLOcbpXO#scrollTo=0SDXyQeB-EeE)**  

---

## 🧠 What You'll Learn

- How to represent optimization problems with Genetic Algorithms
- How to evolve populations over generations
- How to visualize TSP solutions in Python
- How to use Google Colab for AI/optimization projects

---

## 🛠 Dependencies

This project uses basic Python libraries:

```python
import numpy as np
import random
import matplotlib.pyplot as plt
