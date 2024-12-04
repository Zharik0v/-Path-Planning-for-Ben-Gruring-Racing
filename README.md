https://www.bgracing-il.com
# Path Optimization Project – Autonomous Racing Vehicle

## Environment Setup:
 • OS: macOS
 • Jupyter Notebooks (via Anaconda)
 
## Project Overview

The objective of this project was to optimize the path of an autonomous racing bolide by analyzing and refining its trajectory between cones on a racing track. The project is part of a broader effort to engineer an autonomous race car for BGU Racing, with the ultimate goal of competing in and winning international competitions.

Through extensive learning and experimentation, this task focused on creating a smooth and efficient path using advanced mathematical techniques, particularly B-Splines, for path optimization.


## Work and Approach

### Data Preparation

 • Cleaned the dataset by removing empty values.
 • Visualized the cones, marking the left and right sides with different colors.

### Path Calculation and Visualization

 • Calculated the initial path between the cones by determining the average distances.
 • Plotted this initial path for further optimization.

### Path Optimization Methods Evaluated

After reviewing several methods, the decision was made to use B-Splines with Curvature Minimization due to their balance of smoothness and simplicity. Other methods considered but not used include:
 • Clothoid (Euler Spiral): Too complex for achieving optimal path.
 • Hybrid Smoothing Approaches: Not smooth enough .

### Dive into B-Splines

 • Explored B-Splines mathematically, understanding how they approximate curves using control points, degree, and knots.
 • Implemented B-Spline optimization and visualized the final smooth path.
 • Gained insights into curvature minimization and its mathematical expressions, applying these concepts to improve the vehicle’s trajectory.

### Visualization of the Optimized Path

The final path was visualized, demonstrating a significant improvement in smoothness and efficiency compared to the initial path.

## Conclusion

This project not only enhanced my technical skills but also deepened my understanding of mathematical optimization techniques crucial for autonomous vehicle navigation. Joining BGU Racing is an exciting opportunity to apply and further develop these skills, contributing to the team’s mission of engineering a winning autonomous race car.
