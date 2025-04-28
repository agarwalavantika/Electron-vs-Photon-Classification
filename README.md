#  Electron vs Photon Classification | GSoC Project

This project is a part of my GSoC-related work involving the classification of electrons and photons using machine learning techniques. The notebook explores various approaches and preprocessing steps to build an effective classifier, using data provided from a high-energy physics context.

---

##  Project Overview

In high-energy physics experiments, identifying whether a particle is an electron or a photon is crucial. This notebook demonstrates a machine learning pipeline to:

- Preprocess and explore the dataset.
- Engineer relevant features.
- Train and evaluate classification models.
- Visualize performance metrics.

---

##  Contents

- `gsoc-electronphoton-classification.ipynb` – Main Jupyter Notebook with all code and results.
- `data/` – Folder to include dataset files (not included here due to size).
- `models/` – Trained model files (if saved).
- `images/` – Visualizations used in the notebook.

---

##  Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- XGBoost / LightGBM *(if used)*
- Jupyter Notebooks (Kaggle Kernel)

---

##  Model Metrics

- **Accuracy:** 0.7510
- **Precision:**  1.0000
- **F1 Score:** 0.7510
- **Confusion Matrix & ROC Curve**
- ![image](https://github.com/user-attachments/assets/d90148a3-5878-4826-aad7-f00f76a8ca46)
- ![image](https://github.com/user-attachments/assets/88ef0aff-b908-453c-934b-98d546e5f72d)

---

##  Dataset

>  **Note**: The dataset used in this notebook is not included in this repository due to file size limitations or licensing constraints.

- Dataset: _Specify source or whether it's synthetic/Kaggle-provided_
- Features:
  - _List key features used_
- Label:
  - Binary classification: Electron (0), Photon (1)

---

##  Running the Notebook

To run the notebook locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/GSoC_ElectronPhoton_Classification.git
   cd GSoC_ElectronPhoton_Classification
