# NCEM Analysis

A fully working, self-contained setup of Neighborhood-based Cell-cell Interaction Models (NCEMs) for analyzing spatial transcriptomics data.

This repo includes:
- All required NCEM source code
- Jupyter notebooks for training, interaction analysis, and visualization
- Environment YAML file
- Example data directory structure

---

## 📁 Folder Structure

```
ncem-analysis/
├── data/                 # Example data folder (add your own inside here)
│   └── hartmann/
├── env/                 # Conda environment file (environment.yml)
├── notebooks/           # All analysis notebooks
├── src/                 # Source code (copied from original NCEM GitHub)
├── LICENSE
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/jacobson090/ncem-analysis.git
cd ncem-analysis
```

### 2. Create and activate the environment
```bash
conda env create -f env/environment.yml
conda activate ncem_38
```

---

## 🚀 How to Run

Launch Jupyter and open any notebook inside `notebooks/`.  
All dependencies and code are already included. Just press **Run All** ✅

---

## 📌 Notes

- This repo fixes and isolates issues from the original NCEM GitHub project.
- `src/` includes patched files like `interpreter.py` and `ols_fit.py`.
- `data/` is empty by default — use your own spatial data under `data/hartmann/`.

---

## 📧 Contact

Feel free to open an issue or reach out for questions or improvements!

