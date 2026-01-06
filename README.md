# 👥 Netflix User Segmentation (K-Means)

A Streamlit application that segments Netflix users into distinct groups based on their usage patterns and subscription details using K-Means Clustering.

## 📊 Features

- **User Clustering**: Segments users into groups (clusters) to identify behavior patterns.
- **Optimal K Finding**: Uses the Elbow Method to determine the best number of clusters.
- **Interactive Visualization**: 2D scatter plots mapping relationships between different user features.
- **Real-time Processing**: Trains the clustering algorithm instantly on the provided dataset.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vibin-007/k-means.git
   cd k-means
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## 📁 Project Structure

- `app.py`: Main application file containing the Streamlit interface and logic.
- `netflix.csv`: Dataset containing User ID, Subscription Type, Monthly Revenue, Age, and more.
- `kmeans_analysis.ipynb`: Jupyter notebook for clustering analysis and visualization.
- `requirements.txt`: List of Python dependencies.

## 📈 Model Information

The model uses **K-Means Clustering** to group users based on:
- **Monthly Revenue**
- **Age**
- **Join Date** (Duration)
- **Device Usage**
- **Country**
