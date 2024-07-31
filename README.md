Assignment Solutions for Flight Path Optimization, Apple Distribution, and Castle Pathfinding
Overview
This repository contains solutions for three distinct problems: Flight Path Optimization, Apple Distribution, and Castle Pathfinding. Each solution is implemented in Python and includes comprehensive explanations of the approach used.

Problem 1: Flight Path Optimization
Objective
Find non-intersecting paths for flight routes.

Approach
Input Processing: Flight paths are processed to convert string coordinates into tuples of integers.
Geometric Checks: Uses geometric algorithms to check for intersecting line segments between paths.
Path Adjustment: If intersections are detected, paths are adjusted to avoid them.
Visualization: The resulting non-intersecting paths are plotted using Matplotlib.
How to Run
Ensure you have Matplotlib installed: pip install matplotlib
Execute the script to see the output and the plotted paths.
Resources
Geometric Algorithms for Line Intersections
Matplotlib Visualization
Problem 2: Apple Distribution
Objective
Distribute apples among Ram, Sham, and Rahim based on ideal weights.

Approach
Input Collection: Apple weights are collected from the user.
Weight Calculation: Ideal distribution weights for Ram (50%), Sham (30%), and Rahim (20%) are calculated.
Apple Allocation: Apples are allocated while adhering to the calculated proportions.
Result Display: The distribution result is displayed with total weights and percentages.
How to Run
Run the script and input apple weights as prompted.
Resources
Python List Operations and Sorting
Basic Python Input and Validation
Problem 3: Castle Pathfinding
Objective
Find valid paths starting from a castle and visiting all soldiers.

Approach
Input Collection: Collect coordinates for soldiers and the castle.
Recursive Backtracking: Explore all possible paths using recursive backtracking to ensure valid movements.
Path Validation: Ensure each path adheres to movement constraints and returns to the castle.
Result Display: Display all valid paths found.
How to Run
Run the script and input coordinates as prompted.
Resources
Recursive Algorithms
Grid-based Pathfinding
Getting Started
Prerequisites
Python 3.x
Matplotlib (for Problem 1)

Run each script individually:


python flight_path_optimization.py
python apple_distribution.py
python castle_pathfinding.py
Contact
For any questions or further clarification, feel free to reach out:

Name: Sameer Parmar
Email: sameerparmar.sp@gmail.com
