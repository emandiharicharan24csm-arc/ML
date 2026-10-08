# ⚡ Electricity Consumption Anomaly Detection
## Using Unsupervised Machine Learning

A beginner-friendly mini project that detects unusual electricity consumption patterns using unsupervised machine learning — no labelled data required!

---

## 📁 Folder Structure

```
electricity-anomaly-detection/
│
├── data/
│   ├── LD2011_2014.txt          ← Original UCI dataset (711 MB)
│   ├── electricity_subset.csv   ← Subset used (created in Step 1)
│   └── step1_preview_plot.png   ← Preview plot (created in Step 1)
│
├── notebooks/
│   └── electricity_anomaly_detection.ipynb  ← Main project notebook
│
└── README.md
```

---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository — ElectricityLoadDiagrams20112014](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014)
- **Size:** ~711 MB (140,256 rows × 370 columns)
- **Subset Used:** 10,000 rows × 50 clients (~3.5 months of data)
- **Frequency:** Electricity readings every 15 minutes

---

## 🔬 Project Flow

```
Dataset (LD2011_2014.txt)
        ↓
Data Preprocessing     → Handle missing values, normalize data
        ↓
Feature Extraction     → Average, Max, Min, Std per client
        ↓
K-Means Clustering     → Group similar consumption patterns
        ↓
PCA                    → Reduce to 2D for visualization
        ↓
Isolation Forest       → Detect anomalous consumption
        ↓
Normal / Anomalous     → Label each record
        ↓
Graphs & Results
```

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3 | Main programming language |
| Jupyter Notebook | Interactive development environment |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Graphs and visualizations |
| Scikit-learn | K-Means, PCA, Isolation Forest |

---

## 🚀 How to Run

1. Open a terminal in this folder
2. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
3. Open `notebooks/electricity_anomaly_detection.ipynb`
4. Run cells one by one from top to bottom

---

## 📌 Project Steps

| Step | Topic | Status |
|------|-------|--------|
| Step 1 | Dataset Loading & Exploration | ✅ Done |
| Step 2 | Data Preprocessing | 🔄 Next |
| Step 3 | Feature Extraction | ⏳ Pending |
| Step 4 | K-Means Clustering | ⏳ Pending |
| Step 5 | PCA | ⏳ Pending |
| Step 6 | Isolation Forest | ⏳ Pending |
| Step 7 | Visualization | ⏳ Pending |
| Step 8 | Results & Conclusions | ⏳ Pending |

---

*Mini Project — CSM Department | Beginner Level*
