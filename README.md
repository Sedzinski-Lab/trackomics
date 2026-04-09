# trackomics (v1_paper)

This repository contains the code for data postprocessing, plotting, and analysis associated with the study: **Single-cell morphodynamics predict cell fate decisions during mucociliary epithelial differentiation.** Tolonen et al. Molecular Systems Biology, 2026

## Project Resources

The datasets and computer code produced in this study are available in the following databases:

* **Image Data Processing Workflow:** [CopenhagenWorkflow (Github)](https://github.com/kapoorlab/CopenhagenWorkflow)
* **Deep Learning Models:** [Xenopus_Models (Huggingface)](https://huggingface.co/datasets/KapoorLabs-Copenhagen/Xenopus_Models/tree/main)
* **Source Microscopy Data:** [BioImage Data Archive S-BIAD2969](https://doi.org/10.6019/S-BIAD2969)
* **Source Data for Figures:** [BioStudies S-BSST2777](https://doi.org/10.6019/S-BSST2777) (Includes processed data required to run the notebooks in this repo)

---

## Installation & Environment

While this repository consists of Jupyter Notebooks, specific library versions are required to ensure the analysis remains reproducible. We recommend using **Conda** to manage the environment.

### 1. Setup the Environment
To replicate the environment used in this study, you can use the provided `environment.yml` file:

```bash
# Create the environment
conda env create -f environment.yml

# Activate the environment
conda activate trackomics

### 2. Running the Notebooks
Download the required data from the BioStudies S-BSST2777 database.

Ensure the data is placed in the directory structure expected by the notebooks (or update the file paths within the notebooks).
