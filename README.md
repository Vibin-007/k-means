# 👥 Netflix User Segmentation (K-Means)

This project implements **K-Means Clustering** to segment Netflix users based on their usage metadata.

## 🚀 Features

- **Clustering**: Groups users by features like `Age`, `Monthly Revenue`, `Download Speed`.
- **Elbow Method**: Visualizes the optimal number of clusters (`k`).
- **Interactive Scatter Plot**: Explore clusters by plotting different features against each other.

## 🛠️ Usage

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the App**:
   ```bash
   python -m streamlit run app.py
   ```

## 📂 Dataset

The project uses `netflix_cleaned_20251011_141144.csv`. Ensure it is in the root directory.

## 📦 Requirements

- streamlit
- pandas
- scikit-learn
- matplotlib
- seaborn
