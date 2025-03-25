# Data Master_HQ

This application, built with Streamlit, provides a comprehensive suite for data upload, cleaning, analysis, and report generation. It's designed to streamline the process of extracting insights from various datasets through an intuitive user interface.

## 🚀 Overview
**DataMaster** is a production-grade analytics platform built with Streamlit that enables end-to-end data analysis workflows. From raw data ingestion to automated report generation, it provides:

- **Data Profiling** (Missing values, distributions, data types)
- **AI-Powered Cleaning Suggestions** (Outlier detection, duplicate removal)
- **Advanced Analytics** (Temporal trends, clustering, PCA, correlation analysis)
- **Executive Reporting** (Excel exports with pivot tables/visualizations)

Designed for analysts and data scientists seeking reproducibility and operational efficiency.

---

## 🔥 Key Features
| Module | Capabilities | Technologies Used |
|--------|--------------|-------------------|
| **Data Upload** | CSV/Excel/JSON support • Column filtering • Auto-type detection | `Pandas` `Streamlit` |
| **Data Cleaning** | Missing value handling • Outlier removal (Z-Score/IQR) • Feature scaling • One-hot encoding | `Scipy` `scikit-learn` |
| **Advanced Analytics** | Time-series analysis • Cluster analysis (K-Means) • Correlation matrices • PCA | `Plotly` `scikit-learn` |
| **Reporting** | Automated Excel reports • Pivot tables • Downloadable outputs | `OpenPyXL` `Base64` |

---

## ⚙️ Tech Stack
- **Frontend**: `Streamlit`  
- **Data Processing**: `Pandas` `NumPy`  
- **Machine Learning**: `scikit-learn` (PCA, K-Means)  
- **Visualization**: `Plotly`  
- **Utilities**: `Scipy` (statistics), `OpenPyXL` (Excel reporting)  

---

## 🛠️ Installation
1. **Clone Repository**:
   ```bash
   git clone https://github.com/SaburBello/DataMaster.git
   cd DataMaster
