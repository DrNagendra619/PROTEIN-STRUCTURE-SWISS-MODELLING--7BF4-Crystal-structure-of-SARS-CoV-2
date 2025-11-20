# PROTEIN-STRUCTURE-SWISS-MODELLING--7BF4-Crystal-structure-of-SARS-CoV-2
PROTEIN-STRUCTURE-MODELLING [SWISS MODELLING]-7BF4-Crystal-structure-of-SARS-CoV-2-macrodomain-in-complex-with-GMP-
# Homology Modeling: SARS-CoV-2 Macrodomain (NSP3) Structure Prediction 🦠💻

## Overview

This repository contains the complete results of a **Homology Modeling** project performed using the **SWISS-MODEL Server**. The goal was to generate a highly accurate 3D structural model of the **SARS-CoV-2 Macrodomain (NSP3)**, based on a sequence labeled **`7BF4 mutated.fasta`**.

The results indicate an exceptionally high-quality prediction, owing to the near-perfect match with experimentally solved SARS-CoV-2 macrodomain structures.

---

## Target System and Methodology

* **Target Protein:** SARS-CoV-2 Macrodomain (part of Non-Structural Protein 3 / NSP3).
* **Modeling Tool:** SWISS-MODEL Server.
* **Key Template Used:** The modeling utilized templates like **PDB ID: 6z5t** (SARS-CoV-2 Macrodomain in complex with ADP-ribose), demonstrating strong domain knowledge and context.
* **Predicted Oligo-State:** **Monomer**.

### Key Model Quality Metrics
The high quality of the prediction is confirmed by the following metrics:

| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **Global Model Quality Estimate (GMQE)** | **0.96** | Excellent score (closer to 1.0 is better), indicating very high reliability of the overall fold. |
| **QMEANDisCo Global** | $\mathbf{0.90 \pm 0.07}$ | High score, suggesting the model quality is comparable to high-resolution experimental structures. |
| **Template Identity** | **~98.83% - 99.41%** | Extremely high sequence similarity with the best template structures, guaranteeing structural accuracy. |

---

## Repository Files

The files are categorized into the final structural output, and detailed quality reports:

### 🔬 Output Structure & Reports

| File Name | Description |
| :--- | :--- |
| `model_01.pdb` | **The final predicted 3D structure** of the SARS-CoV-2 Macrodomain in standard PDB format. |
| `report.html` | The full, interactive **SWISS-MODEL report**, containing all visualization charts, sequence alignment, and detailed metrics. |
| `models.html` / `templates.html` | Interactive files used for browsing model and template comparison within the report interface. |
| `7BF4 mutated.fasta _ Summary.pdf` | Summary report including the target sequence, template filtering results, and global quality metrics. |
| `7BF4 mutated.fasta _ Models.pdf` | Report containing residue-by-residue local quality estimates and alignment details. |
| `7BF4 mutated.fasta _ Templates.pdf` | Full list of all templates identified and their quality scores. |

### 📈 Quality Visualizations

| File Name | Purpose |
| :--- | :--- |
| `Local_quality_estimate.png` | Graphical representation of the residue-by-residue local quality score (QMEANDisCo). |
| `Quality_comparison.png` | Graph comparing the model's overall quality (QMEAN) against the quality distribution of similar experimental structures. |
| `01.png` | Additional visualization output (likely a secondary plot from the server). |

---

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **Analyze the 3D Structure:**
    Load the **`model_01.pdb`** file into any molecular visualization software (e.g., **PyMOL**, **ChimeraX**, or **VMD**) to inspect the predicted 3D structure and potential ligand-binding sites.

3.  **Review the Full Report:**
    Open the **`report.html`** file in a web browser to view the interactive quality assessment, detailed template alignments, and residue-specific confidence scores.
