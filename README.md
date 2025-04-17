# Multi-objective Optimisation of Path and Space Utilisation in Landscape Garden Design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)

This repository implements multi-objective optimization algorithms for landscape garden design, focusing on:
**Space utilization efficiency** (maximized)
**Path length** (minimized) 
**Aesthetic quality** (maximized)

Tested on Beijing's Tongzhou District (906 km² urban area with 2200 persons/km² density).

## Key Features
Comparative analysis of 5 algorithms: MOEAs, GA, PSO, ACO, SA
Real-world case study with ArcGIS spatial data
Pareto-optimal solution visualization
Weighted objective handling (path priority, aesthetic components)

## 📊 Results Summary
| Algorithm | Space Utilization | Path Length | Aesthetic Score |
|-----------|------------------:|------------:|----------------:|
| MOEAs     | **90.2%**         | **140.3m**  | **9.2/10**      |
| GA        | 85.3%             | 150.2m      | 8.4/10          |
| PSO       | 88.5%             | 148.6m      | 8.6/10          |


## 🛠 Installation
```bash
git clone https://github.com/yourusername/landscape-optimization.git
cd landscape-optimization
conda env create -f environment.yml  # Python 3.8+ required
conda activate landscape-opt
