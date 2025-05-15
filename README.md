# spectrograph-notebook
A **Jupyter Notebook** that helps spectroheliograph design based on Ken Harrison's spreadsheet **SHGV1_3-SolEx.xls**

# 🌞 Solar Spectrograph Design Notebook

This repository contains an interactive Jupyter Notebook for modeling and analyzing a solar spectrograph system. It includes:

- Collimator and camera lens geometry
- Grating angle and spectral resolution calculators
- Solar disk projection and plate scale tools
- Camera coverage diagnostics with lens sizing plots
- Interactive widgets for live optical configuration

---

## 📁 Contents

- `Spectrohelioscope.ipynb` — the main interactive modeling notebook
- `README.md` — this file
- `Reflection_Grating_Angles.png`
- `requirements.txt`

---

## ▶️ How to Run

You have two options:

### 🔗 **Run it in Google Colab (Recommended)**

No installation needed. Just click:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdroberts1243/spectrograph-notebook/blob/main/Spectrohelioscope.ipynb)

---

### 💻 **Run Locally (Advanced Users)**

Make sure you have Python 3.8+ and Jupyter installed:

```bash
pip install notebook ipywidgets matplotlib numpy pandas
jupyter notebook
