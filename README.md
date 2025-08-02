# PRO5807 Case Study (2025): Usemore Soap Company

Optimization models for warehouse location and capacity planning using Gurobi. Based on Chapter 14 of "Supply Chain Management" by Ronald H. Ballou.

<div align="center">
  <img src="latex/images/enunciado/figura01.png" alt="Supply Chain Network Diagram" width="45%" />
  <img src="notebooks/images/mapa_2_problema_3.png" alt="Supply Chain Solution" width="45%" />
</div>

## Quick Start

1. **Prerequisites**: Python 3.11+, Gurobi educational license (see https://support.gurobi.com/hc/en-us/articles/360013195212-Which-Python-versions-are-supported-by-Gurobi)
2. **Setup**:

- Install git and git-lfs
- Install vscode
- Install python (recommended version 3.13 or higher)
- Install Gurobi and activate a license
- Open this repo on vscode
- Create a virtual environment and install dependencies:

   ```bash
   python -m venv .venv
   .venv\Scripts\Activate.ps1  # Windows
   pip install -r requirements.txt
   ```

3. **Run**: Open `notebooks/modelo-gurobi-p1.ipynb` (or p2, p3 for different scenarios)

## Project Structure

- **`notebooks/`**: Three optimization models (P1: baseline, P2: warehouses expansions, P3: production capacity expansion)
- **`distances/`**: Distance matrices generation and geographic data handling
- **`latex/`**: LaTeX report source (you can upload to Overleaf if preferred)
- **`solutions/`**: HTML outputs and visualizations

## Key Files

- `modelo-gurobi-p1.ipynb`: Baseline warehouse optimization
- `modelo-gurobi-p2.ipynb`: With 93% service level requirement
- `modelo-gurobi-p3.ipynb`: With plant capacity expansion options
- `view_solution.ipynb`: Results visualization and mapping


## Development

- Use `make format` before committing.
- The binary files are stored in Git LFS (Large File Storage) to avoid bloating the repository size.
