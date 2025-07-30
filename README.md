# 🫀 Arrhythmia Detection using Python

This project simulates ECG signals and uses real patient data from the MIT-BIH Arrhythmia Database to detect abnormal heart rhythms.

## 🔍 Features
- ECG signal simulation (normal & arrhythmic)
- Real ECG data loading from PhysioNet using `wfdb`
- R-peak detection using custom and library-based methods
- Interval analysis for rhythm classification:
  - Tachycardia
  - Bradycardia
  - Arrhythmia
- Visual plots with highlighted peaks

## 📁 Files Included
- `Arrhythmia_Project.ipynb`: The notebook
- `Arrhythmia_Project.pdf`: Exported PDF (optional)
- `ecg_plot.png`: Image of ECG with R-peaks (optional)
- `README.md`: Project overview
- `LICENSE`: Open-source license
- `.gitignore`: Ignore junk files

## 📊 Tools Used
- Python
- NumPy, Matplotlib, SciPy
- WFDB (PhysioNet)
- Jupyter Notebook

## 🔗 Dataset Source
[MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)

---
## 📈 Sample Output

![ECG Plot](ecg_plot.png)
