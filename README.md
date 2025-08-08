# P-median-Optimization
Facility location optimization using p-median modeling on 13K+ McDonald’s outlets. Benchmarks ILP, Greedy, PAM, GA, and SA for runtime vs. solution trade-offs. Includes full dataset pipeline, code, and report.


# 🗺️ McDonald's Outlet Optimization using the p-Median Problem

This project applies facility location optimization techniques to a dataset of 13,000+ McDonald's outlets across the USA. We compare several algorithms—including ILP, Greedy, PAM, Genetic Algorithm (GA), and Simulated Annealing (SA)—on solution quality and runtime efficiency.

## 📊 Problem Statement

Formulate and solve the p-median problem to determine optimal hub locations minimizing the total distance between each store and its nearest hub. Evaluate different algorithmic strategies for scalability and performance.

## 🧪 Algorithms Implemented

- Haversine Formula(for distance calculation)
- Brute Force (Exact)
- Integer Linear Programming (ILP)
- Greedy Heuristic
- Partitioning Around Medoids (PAM)
- Genetic Algorithm (GA)
- Simulated Annealing (SA)

## 🧰 Tools & Libraries

- Python, Pandas, NumPy, SciPy
- PuLP (for ILP)
- Matplotlib & Seaborn (for graphing results)

## 🗂️ Dataset

- [McDonald’s Locations 2025 – Kaggle](https://www.kaggle.com/datasets/jacopomazzoni/mcdonalds-locations-2025)

## 📄 Project Report

- [Read Full Report (PDF)](https://drive.google.com/file/d/1DFmBVv8be5E9Jj3JTXpGpH4sKDnuFoPl/view?usp=drive_link)


## 🚀 Future Work
- Incorporate deep reinforcement learning for scalable heuristics
- Evaluate modern solvers like Gurobi, OR-Tools
- Experiment with hybrid metaheuristics

## 📬 Contact
Created by [Lokesh Joshi](https://www.linkedin.com/in/lokesh-j-819181336/) | [GitHub](https://github.com/Blanca-Vern-2nd)
