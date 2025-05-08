
- **`code.ipynb`**: All data processing, analysis, and plotting code in one Colab notebook.  
- **`files_for_project/`**: Data and stimulus assets needed by the notebook.

---

## Prerequisites

- **Google Colab** (recommended) or local Jupyter  
- **Python 3.8+**  
- **Libraries** (installed in Colab or via pip):  
  ```bash
  pip install pandas numpy matplotlib

How to Run
Open code.ipynb in Google Colab.

Mount Google Drive when prompted (so the notebook can read/write from files_for_project/).

Run all cells in order:

Stimulus generation (if needed)

Data loading and preprocessing

Analyses and figure generation (Figures 2–5)

Review the resulting plots directly in the notebook, or find saved images under files_for_project/ subfolders.

Code Organization
Within code.ipynb, sections are organized as:

Setup & Mounting

Stimulus Generation

Loading Participant Data

Merging with Metadata & Answer Key

Computing Accuracy & RT Metrics

Percent-Difference Calculations & Bootstrapping

Figures

Vis 1: Polarity and Chart-Type Impact

Vis 2: Performance Advantage by Polarity

Vis 3: Preference vs. Performance Alignment

Each section is clearly documented with headings and inline comments.

Notes
All file paths in the notebook assume files_for_project/ is in your Colab drive root. Adjust BASE_DIR at the top of the notebook if your path differs.

The sample size is small (N=8); results are illustrative. For a larger study, replace the trial_data/ folder with your full dataset.

Contact
Questions or issues? Please open an issue or contact Your Name at sasad1@tulane.edu.
