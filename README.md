## How to Run

1. **Open** `code.ipynb` in Google Colab.  
2. **Mount Google Drive** when prompted (so the notebook can read/write from `files_for_project/`).  
3. **Run all cells** in order:  
   - Stimulus generation (if needed)  
   - Data loading and preprocessing  
   - Analyses and figure generation (Figures 2–5)  
4. **Review** the resulting plots directly in the notebook, or find saved images under `files_for_project/` subfolders.

---

## Code Organization

Within **`code.ipynb`**, sections are organized as:

1. **Setup & Mounting**  
2. **Stimulus Generation**  
3. **Loading Participant Data**  
4. **Merging with Metadata & Answer Key**  
5. **Computing Accuracy & RT Metrics**  
6. **Percent‐Difference Calculations & Bootstrapping**  
7. **Figures**  
   - Vis 1: Polarity and Chart‐Type Impact  
   - Vis 2: Performance Advantage by Polarity  
   - Vis 3: Preference vs. Performance Alignment  

Each section includes headings and inline comments for clarity.

---

## Notes

- All file paths in the notebook assume **`files_for_project/`** is in your Colab Drive root. Adjust `BASE_DIR` at the top of the notebook if your path differs.  
- Sample size is small (N=8); results are illustrative. For a larger study, replace the `trial_data/` folder with your full dataset.

---

## Contact

Questions or issues? Please open an issue or contact **Your Name** at `sasad1@tulane.edu`.  

