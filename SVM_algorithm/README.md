# 🌟 CIFAR-10 Classification with SVM

![Image](https://github.com/user-attachments/assets/5b35dce7-f790-4824-af0b-bb2da7f4025d)

## 📖 Overview

This Jupyter Notebook showcases a robust classification pipeline for the **CIFAR-10 dataset** using **Support Vector Machines (SVM)**. The CIFAR-10 dataset includes 60,000 32x32 color images across 10 classes (e.g., ✈️ airplane, 🚗 car, 🐦 bird), with 50,000 training and 10,000 test images. The project covers data preprocessing, SVM modeling, hyperparameter tuning, and detailed evaluation with visualizations.

### ✨ Key Features
- 🛠️ Preprocessing and subsampling of CIFAR-10.
- 🤖 Training SVMs with RBF and linear kernels.
- 🔧 Hyperparameter optimization via GridSearchCV.
- 📊 Analysis of support vectors and decision boundaries.
- 🎨 Visualizations: confusion matrices, errors, and dataset examples.

The notebook uses a subsampled dataset (default: 5,000 samples) with a 70% train / 30% test split for efficiency.

---

## 🛠️ Prerequisites

### 💻 Software
- **Python 3.6+**: Core language.
- **Jupyter Notebook**: Interactive environment.

### 📦 Python Libraries
Install with:
```bash
pip install numpy matplotlib seaborn tensorflow scikit-learn
```
- `numpy` 🧮: Numerical operations.
- `matplotlib` 📈: Plotting.
- `seaborn` 🎨: Enhanced visualizations.
- `tensorflow` ⚙️: CIFAR-10 dataset loading.
- `scikit-learn` 🤓: SVM, PCA, and metrics.

### ⚡ Hardware
- Moderate specs (4GB RAM, multi-core CPU). Multi-core recommended for faster tuning.

---

## 🚀 Usage

1. **📥 Get the Notebook**:
   - Download `CIFAR10_SVM_Classification.ipynb`.

2. **🌐 Set Up Environment**:
   - Install libraries (see above).
   - Ensure internet access for dataset download.

3. **▶️ Run It**:
   - Launch Jupyter:
     ```bash
     jupyter notebook CIFAR10_SVM_Classification.ipynb
     ```
   - Run all cells or step through manually.

4. **🔍 Key Sections**:
   - **Preprocessing** 🧹: Loads and subsamples CIFAR-10.
   - **SVM Training** ⚡: RBF and linear models.
   - **Tuning** 🔧: Optimizes hyperparameters.
   - **Evaluation** 📊: Metrics and visualizations.

5. **✨ Customize**:
   - Adjust `n_samples` in `charger_et_preparer_donnees()`.
   - Modify `param_grid` for tuning.
   - Uncomment optional visualizations.

---

## 🎉 Output

- **Text** 📜: Data shapes, metrics, and summaries.
- **Visuals** 🖼️:
  - Random dataset examples 🌈.
  - Decision boundaries (PCA) 📉.
  - Confusion matrices 🎨.
  - Performance bar charts 📊.
  - Classification errors 🔍.

---

## ⚠️ Notes

- **Missing Import** 🚨: Add `import pandas as pd` for the performance table:
  ```python
  import pandas as pd
  ```
  Install: `pip install pandas`.

- **Time** ⏱️: Tuning may take time; adjust `n_samples` as needed.
- **Commented Code** 💤: Uncomment `joblib` lines to save models (`pip install joblib`).

---

## 🚧 Limitations

- Subsampling may reduce generalization.
- 2D PCA visualization simplifies data.
- Limited hyperparameter grid for speed.

## 🌱 Future Improvements

- Use full dataset with better hardware.
- Add more kernels or ensembles.
- Implement data augmentation.

---

## 📜 License

For educational use only. CIFAR-10 terms apply.

## 📬 Contact

Questions? Reach out at [malakzaidi815@gmail.com]!
