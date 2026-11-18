# drone-route-optimizer

A genetic algorithm that optimizes drone delivery routes in 3D space.

> Coursework · Linear Algebra · 2024-2 · finished

## Goal
Go beyond plain route optimization: the algorithm also handles fuel, cargo to deliver,
refuelling points and sub-routes, so one complex route can be split across several
drones flying in parallel. A Blender animation shows the drones finding and sharing routes.

<img width="800" alt="Drone routes" src="https://github.com/user-attachments/assets/f9ee3163-89e1-4e21-b5ae-44b652448efc" />

## Stack
- Python, NumPy, Matplotlib (3D plots)
- Genetic algorithm (evolutionary optimization)
- Blender (`Modelo3D.blend`, animation)

## How to run
```bash
pip install numpy matplotlib
python OtimizadorDeRotas.py
```

## What I took from it
- How to use a genetic algorithm to solve travelling-salesman-style problems.
- How to use Blender to demonstrate how an algorithm works.
