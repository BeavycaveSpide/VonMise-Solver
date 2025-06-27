# VonMise-Solver
# 📊 Failure Analysis of a Cylindrical Pin

This repository contains a Jupyter Notebook that performs **failure analysis** for a cylindrical pin used to hold a container door. The analysis investigates how varying the **diameter** (`d`) and **length** (`L`) of the pin affects the stress it experiences, using a combination of **symbolic calculations** and **numerical visualizations**.

## 📝 Description

The notebook walks through the following:

- Defining the mechanical scenario and the forces acting on the pin.
- Using **SymPy** for symbolic equilibrium analysis to derive internal forces.
- Exploring different dimensions of the pin (`d`, `L`) to compute bending and shear stresses.
- Generating **heatmaps and 3D plots** to visualize stress distribution under varying conditions.
- Identifying safe design regions based on stress thresholds.

## 🛠️ Used Libraries

- `numpy`: Numerical computation
- `sympy`: Symbolic math
- `matplotlib`: 2D plotting
- `plotly`: Interactive 3D plotting

## 📁 File Contents

- `FailiureAnalysis.ipynb`: Main notebook
- (Optional) `images/`: Exported plots
- (Optional) `results/`: Processed output data

## 📈 Example Output

- Heatmaps and 3D plots of stress versus pin dimensions

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/failure-analysis.git
cd failure-analysis
pip install numpy sympy matplotlib plotly
jupyter notebook FailiureAnalysis.ipynb
