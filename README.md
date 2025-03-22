# BugPrioritizationScheduler Using SAT Solver

## Overview

This project aims to optimize bug fix prioritization by modeling the problem as a **SAT** (Satisfiability) problem. The solution integrates various factors like **bug severity**, **time to fix**, and **developer availability**, and also accounts for **dependencies between bugs**. Visualizations such as **Gantt charts**, **heatmaps**, **dependency graphs**, and an **animated timeline** provide insights into the bug resolution process.

## Features

- **Bug Fix Prioritization**: Using SAT solver to model and optimize the order in which bugs should be resolved.
- **Bug Dependencies**: Handles bug dependencies to ensure that dependent bugs are fixed in the correct order.
- **Developer Availability**: Incorporates developer availability to balance the bug fixing load.
- **Visualizations**: Generates Gantt charts, heatmaps, radial graphs, bubble charts, and animated timelines for better understanding.

## Visualizations

1. **Gantt Chart**: Displays bug fix timelines based on start times and developer availability.
2. **Heatmap**: Shows the relationship between bug severity and time-to-fix.
3. **Radial Dependency Graph**: Visual representation of dependencies between bugs.
4. **Bubble Chart**: Displays bug prioritization based on severity, time to fix, and developer availability.
5. **Animated Timeline**: Displays the timeline of bug fixes as an animated sequence.


## Installation

### Prerequisites
1. **Python 3.x**
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt

## Required Libraries

-pandas
-networkx
-matplotlib
-plotly
-seaborn
-pysat

# Usage
1. Clone the repository:
  ```bash
  git clone https://github.com/yourusername/Bug-Prioritization-Scheduler.git
  cd bug-fix-prioritization
  ```
2. Run The Project:
  ```python run_all.py```

## This script will:
1. Clean and preprocess the bug dataset.
2. Run the SAT solver to generate the bug fix schedule.
3. Generate and save the visualizations (Gantt chart, heatmap, etc.).

# Outputs
1. Priority Queue: A CSV file (final_prioritized_bugs.csv) containing the prioritized list of bugs.
2. Visualizations: The visual outputs (charts, graphs) are saved in the results/ directory.

## Generated Visualizations
1. Gantt Chart
2. Severity vs Time-to-Fix Heatmap
3. Radial Dependency Graph
4. Bug Prioritization Bubble Chart
5. Animated Bug Fix Timeline

# Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.
 

