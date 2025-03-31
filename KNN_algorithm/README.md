# 🌟 Mushroom Classification with KNN 🍄

![Image](https://github.com/user-attachments/assets/5cfc57e8-d096-42ed-906b-fd7f751e99d5)

## 📖 Overview

Welcome to this exciting project by **Malak Zaidi**! 🎉 This Jupyter Notebook uses the **K-Nearest Neighbors (KNN)** algorithm to classify mushrooms as **edible** or **poisonous** based on the Agaricus Lepiota dataset from the UCI Machine Learning Repository. The dataset contains 8,124 samples with 22 categorical features describing mushroom characteristics.

### ✨ Key Features
- 🧹 **Data Exploration**: Analyzes correlations and preprocesses the dataset.
- 📊 **Visualization**: Displays data in 2D/3D using PCA and decision boundaries.
- ⚙️ **KNN Tuning**: Tests various `k` values and distance metrics (Euclidean, Manhattan, Minkowski).
- 🔍 **Feature Importance**: Uses SHAP and permutation importance for insights.
- 🤖 **Model Comparison**: Compares KNN with Random Forest.
- 🎨 **Results**: Includes confusion matrices, accuracy, recall, and F1-score visualizations.

The notebook aims to optimize KNN for high accuracy while exploring how `k` and distance metrics impact classification.

---

## 🛠️ Prerequisites

### 💻 Software
- **Python 3.6+**: Core language.
- **Jupyter Notebook**: Interactive environment.

### 📦 Python Libraries
Install with:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn ipywidgets
```
- `numpy` 🧮: Numerical operations.
- `pandas` 📋: Data handling.
- `matplotlib` 📈: Plotting.
- `seaborn` 🎨: Enhanced visualizations.
- `scikit-learn` 🤓: KNN, PCA, and metrics.
- `ipywidgets` ⚡: Interactive elements.

### ⚡ Hardware
- Moderate specs (4GB RAM, multi-core CPU). Multi-core recommended for cross-validation.

### 🌐 Dataset
- Automatically downloaded from UCI: [Agaricus Lepiota](https://archive.ics.uci.edu/ml/machine-learning-databases/mushroom/agaricus-lepiota.data).

---

## 🚀 Usage

1. **📥 Get the Notebook**:
   - Download `Mushroom_KNN_Classification.ipynb`.

2. **🌐 Set Up Environment**:
   - Install libraries (see above).
   - Ensure internet access for dataset download.

3. **▶️ Run It**:
   - Launch Jupyter:
     ```bash
     jupyter notebook Mushroom_KNN_Classification.ipynb
     ```
   - Run all cells or step through manually.

4. **🔍 Key Sections**:
   - **Data Prep** 🧹: Loads, encodes, and scales the dataset.
   - **Exploration** 📊: Correlation heatmap and PCA plots.
   - **KNN Training** ⚡: Cross-validates multiple configurations.
   - **Evaluation** 📈: Metrics and visualizations for best model.

5. **✨ Customize**:
   - Modify `k` values or distance metrics in the `configurations` list.
   - Adjust PCA dimensions or visualization settings.

---

## 🎉 Output

- **Text** 📜: 
  - Dataset stats (e.g., duplicates).
  - Cross-validation results (accuracy, recall, F1) with standard deviations.
  - Best model details and test set performance.
- **Visuals** 🖼️:
  - Correlation heatmap 🌡️.
  - PCA scatter plots (2D/3D) 📉.
  - Bar plots for metrics by `k` and distance 🎨.
  - Decision boundary visualizations 🗺️.

### 🌟 Highlight
- Best Model: **K=1, Manhattan Distance** achieves **99.94% accuracy** on the test set!

---

## ⚠️ Notes

- **Data Preprocessing**: Missing values in `stalk-root` are filled with the mode.
- **Dependencies**: Ensure all libraries are installed; `ipywidgets` is optional for interactivity.
- **Execution Time** ⏱️: Cross-validation may take a few minutes depending on hardware.

---

## 🚧 Limitations

- KNN assumes feature independence, which may not fully hold for mushroom traits.
- High-dimensional categorical data may limit PCA visualization effectiveness.
- Small `k` values risk overfitting; larger `k` may smooth decision boundaries excessively.

## 🌱 Future Improvements

- Test additional distance metrics or feature selection methods.
- Incorporate data augmentation or synthetic samples.
- Explore ensemble methods beyond Random Forest.

---

## 📜 License

For educational use only. The Agaricus Lepiota dataset is subject to UCI terms.

## 📬 Contact

Questions? Reach out to **Malak Zaidi** !
