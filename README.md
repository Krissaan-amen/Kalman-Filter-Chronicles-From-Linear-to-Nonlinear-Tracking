# Kalman Filter Chronicles: From Linear to Nonlinear Tracking

<p align="center">
  <img src="Pic\Lab.png" width="40%" />
</p>

## Project Overview
This repository takes you on a journey through the fascinating world of Kalman filtering! Watch as we evolve from basic linear filters to advanced nonlinear techniques for tracking objects that refuse to move in straight lines.

## Lab 1: Linear Kalman Filtering - The Basics
In this first adventure, we track an object moving in 2D space using the classic Kalman filter:

### Features
- **Time-Travel Simulation**: Create continuous and discrete-time models of object movement
- **Real-Time Tracking**: Implement causal Kalman filter that only uses past and present data
- **Crystal Ball Mode**: Apply Kalman smoother to peek into the future for better estimates
- **Pretty Pictures**: Visualize everything with fancy plots and confidence bounds

### Discoveries
- Position estimates are surprisingly good! 
- Velocity estimates get a bit... wild 
- Smoothing makes everything better (if you can wait for future data)

## 🧙‍♂️ Lab 2: Nonlinear Kalman Filtering - The Advanced Stuff
When objects start moving in mysterious ways, we need more powerful magic:

### ✨ Features
- **Object Simulation**: Moving target with Wiener velocity model
- **EKF Sorcery**: Extended Kalman Filter that linearizes the nonlinear world
- **UKF Wizardry**: Unscented Kalman Filter that samples the nonlinear universe
- **Battle of Filters**: Epic showdown between EKF and UKF with RMSE metrics

### Discoveries
- Both filters successfully track the nonlinear movement
- UKF slightly outperforms EKF for position estimation
- Turns out, approximating nonlinear systems is tricky business!

## Requirements
- Python 3.x (the more x, the better)
- NumPy (for math magic)
- Matplotlib (for pretty pictures)

##  How to Run
1. Clone this repo faster than a Kalman filter predicts positions
2. Open the Jupyter notebooks (`Lab_1.ipynb` and Lab_2.ipynb)
3. Run all cells sequentially (or randomly, but you might get chaos)
4. Marvel at the tracking prowess of these algorithms!

## What You'll Learn
- How Kalman filters make order out of noisy chaos
- Why smoothers are like time machines for your data
- When to use EKF vs UKF (hint: it's all about the nonlinearity)
- The joy of watching colored lines converge on a plot

## Conclusion
From tracking simple linear motion to handling complex nonlinear trajectories, these labs demonstrate the evolution and power of Kalman filtering techniques. The UKF may have won this round, but the battle for optimal state estimation continues!

*Remember: A good filter is like a good friend - it sticks with you even when you're being noisy and unpredictable.*