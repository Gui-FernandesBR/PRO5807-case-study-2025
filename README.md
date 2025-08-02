# PRO5807 Case Study (2025)

In this repo we solve the Usemore Soap Company case study from the Chapter 14 of the book "Supply Chain Management" by Ronald H. Ballou.

## installation

- Install git and git-lfs
- Install vscode
- Install python (recommended version 3.13 or higher)
- Install Gurobi and activate a license (see https://support.gurobi.com/hc/en-us/articles/360013195212-Which-Python-versions-are-supported-by-Gurobi)
- Open this repo on vscode
- Create a virtual environment

```bash
python -m venv .venv
```

- Activate the virtual environment

```bash
# Windows
.venv\Scripts\Activate.ps1
# Linux
source .venv/bin/activate
```

```bash
# Windows
.venv\Scripts\Activate.ps1
# Linux
source .venv/bin/activate
```

- Install the required packages

```bash
pip install -r requirements.txt
```

- Run the `notebook/modelo-gurobi.ipynb` file
- Before committing, please run the `make format` command to format the code

## Caveats

- The `latex/main.tex` file is responsible for generating the PDF report. If you prefer you can upload the whole `latex` folder to Overleaf and edit the document there.

