# Iris Data Visualization & Insight Report

This project provides a detailed visual exploration of the Iris dataset using Python libraries such as Seaborn, Matplotlib, and Pandas. It includes descriptive statistics, feature distributions, comparative visualizations, and a predictive scatter plot to understand the nature of different flower species.

## Project Overview

The Iris dataset is a classical dataset used to classify three types of iris flowers: Setosa, Versicolor, and Virginica. This notebook demonstrates:

- Histograms for numeric feature distributions
- Boxplots for identifying outliers and spread
- Species-wise comparison of features
- Visualizing where a new flower might fall on the feature space

## Tasks Performed

### 1. Load Dataset
- Loaded the built-in Iris dataset from Seaborn.
- Explored dataset structure and content using `.head()` and `.info()`.

### 2. Histograms
- Displayed distributions for each numeric feature using:
  - Basic histograms with default size
  - Customized histograms with bin size and edge coloring

### 3. Boxplots
- Created boxplots for all numeric columns to detect spread and outliers
- Created species-wise boxplot (e.g., Sepal Length vs Species)

### 4. Overall Feature Comparison
- Melted dataset using `pd.melt()` for advanced visual grouping
- Created grouped boxplots showing all features by species

### 5. Predicting a New Flower's Category
- Manually added a new data point with Petal Length = 5.1 and Petal Width = 1.8
- Plotted this on a scatter plot along with existing species using color and marker encoding
- Helped visually estimate the possible category for the new flower

## Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| Python       | Core language |
| Pandas       | Data manipulation |
| Seaborn      | Statistical visualizations |
| Matplotlib   | Basic plotting |
| Jupyter Notebook | Interactive code development |

## Visual Highlights

- Histogram visualizations to understand feature distribution
- Side-by-side boxplots for species-level feature comparison
- Clean scatter plot with custom legend and highlighted point for prediction

## Folder Structure

```
.
├── Iris_Visualization_Notebook.ipynb
├── README.md
```

## Author

**Afzal Shah**  
BS in Computer Science  
Machine Learning and Data Science Enthusiast
