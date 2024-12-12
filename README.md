![License](https://img.shields.io/badge/license-MIT-blue.svg)

# 📊 Data Analysis Project

## 📝 Introduction
This project is a comprehensive data analysis that covers multiple tasks, including data preprocessing, exploratory data analysis (EDA), regression modeling, clustering, dimensionality reduction, and anomaly detection. The analysis is performed on two datasets:

- **📊 Enhanced Sales Data (enhanced_sales_data.csv)** – used for classification tasks.
- **🖼️ Pixel Data (pixel.txt)** – used for clustering tasks.

The analysis involved several stages, including cleaning, preprocessing, visualization, and modeling to derive meaningful insights.

## 📂 Data Sources
- **📊 Enhanced Sales Data**:
  - Detailed sales information with multiple attributes for classification analysis.
  - **File**: `enhanced_sales_data.csv`

- **🖼️ Pixel Data**:
  - Pixel-level intensity data used for clustering analysis.
  - **File**: `pixel.txt`

- **📄 Report**:
  - Detailed project report outlining the methodology and results.
  - **File**: `Data_Analysis_Project.pdf`

- **📓 Jupyter Notebook**:
  - Python code used for analysis and visualizations.
  - **File**: `Project_Data_Analysis.ipynb`

## 🛠️ Libraries Used
- **🐼 Pandas**: Data manipulation and analysis
- **🔢 NumPy**: Numerical operations
- **📊 Scikit-Learn**: Machine learning and preprocessing
- **📈 Matplotlib & Seaborn**: Data visualization
- **📊 Plotly**: Interactive visualizations

## 📋 Tasks Overview

### 1️⃣ Task 1: Data Acquisition and Preparation
- **🎯 Goal**: Prepare datasets by handling missing values and removing outliers.
- **✅ Steps**:
  - Handled missing values in the Age and Total Sales columns.
  - Detected and removed outliers using the Interquartile Range (IQR) method.

### 2️⃣ Task 2: Exploratory Data Analysis (EDA)
- **🎯 Goal**: Visualize data distributions and relationships.
- **📊 Visualizations**:
  - 📉 Histograms with boxplots
  - 🟢 Scatter plots
  - 🔥 Correlation heatmaps

### 3️⃣ Task 3: Linear Regression
- **🎯 Goal**: Model the relationship between Price per Unit and Total Sales.
- **📈 Results**:
  - 🧮 Coefficient: 2.55
  - ➖ Intercept: -35.22
  - 🏆 R² Values: 0.94 and 0.98

### 4️⃣ Task 4: Decision Tree Regression
- **🎯 Goal**: Predict Total Sales using a decision tree model.
- **🌳 Model**:
  - Features: Price per Unit and Quantity
  - Max Depth: 3

### 5️⃣ Task 5: Clustering Analysis
- **🎯 Goal**: Cluster the pixel data using K-Means and hierarchical clustering.
- **🔍 Results**:
  - ✅ K-Means provided better clustering for high-dimensional data compared to hierarchical clustering.

### 6️⃣ Task 6: Principal Component Analysis (PCA)
- **🎯 Goal**: Enhance clustering results by reducing dimensions.
- **✨ Impact**:
  - 📊 Improved cluster separation
  - 🚀 Reduced noise and computational demand

### 7️⃣ Task 7: Anomaly Detection
- **🎯 Goal**: Detect and remove anomalies to improve clustering.
- **🔎 Technique**:
  - Identified anomalies using distance from cluster centers.
  - ✅ Improved clustering results by removing outliers.

## 🔗 Resources
- 📊 **Enhanced Sales Data**: [Download Here](https://drive.google.com/file/d/1IkO__Ts2ZsRwA4HRsoaS9DM-2pKVpuYT/view)
- 🖼️ **Pixel Classification Data**: [Download Here](https://drive.google.com/file/d/1Xa0VCbA2EDZ8AKIk6UQIGG2KU-rDJa3a/view)

## 📝 Contributors
- Anas Mohammed Al-Subhi
- Nawaf Abdulrhman Al-Ageel
- Faisal Hammad Al-Omari
- Marwan Sohail Alotaibi

## 📜 License
This project is licensed under the MIT License.

## 💬 Feedback and Contributions
- **Contributions**: Feel free to fork the repository and submit pull requests.
- **Issues**: If you encounter any problems or have feature requests, please open an issue.
