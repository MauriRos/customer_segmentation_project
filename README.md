# Customer Segmentation Project

This project uses customer segmentation techniques through marketing analysis to identify distinct groups of consumers based on demographic and purchasing behavior characteristics. The main focus is to apply **Principal Component Analysis (PCA)** and **Clustering** (K-Means) to create customer profiles that could be used for targeted marketing strategies.

## Project Contents

- **Customer Segmentation**: Using the marketing dataset, the project classifies customers into different segments to optimize marketing campaigns.
- **Visualization**: Detailed plots like heatmaps, distributions, and 3D plots to explore different customer segments.
- **Analysis**: Analysis of the key characteristics of the generated clusters, such as income, age, family size, education, etc.

## Project Structure

customer_segmentation_project/
├── data/
│   └── marketing_campaign.csv          # Dataset containing customer data
├── images/
│   ├── 2D_Scatter_Plot.png            # 2D scatter plot of segmentation 
│   ├── 3D_Scatter_Plot.png            # 3D scatter plot of segmentation 
│   ├── Elbow_Method.png               # Elbow method for determining the number of clusters 
│   ├── Pairplot.png                   # Pairplot of feature relationships 
│   └── ...                            # Other plots generated during the analysis
├── notebooks/
│   └── customer_segmentation_project.ipynb  # Notebook with data analysis 
├── requirements.txt                  # Project dependencies
└── README.md                         # This file



## Requirements

To run this project, you need to install the following Python libraries:

- **Data manipulation**:
  - `pandas`
  - `numpy`

- **Visualization**:
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `altair`
  - `mpl_toolkits`

- **Preprocessing and Clustering**:
  - `sklearn`

- **Other Utilities**:
  - `google.colab`

## File Descriptions

- **`marketing_campaign.csv`**: Contains customer data, with features such as age, income, number of children, education level, etc.
  
- **`customer_segmentation_project.ipynb`**: The main Jupyter Notebook where the segmentation analysis is performed. The code covers everything from data loading to result visualization, including data cleaning and segmentation using PCA and K-Means.

- **`images/`**: This folder contains the plots generated during the analysis, such as 2D and 3D scatter plots of the clusters, the elbow method for determining the optimal number of clusters, and more.

## Results

The analysis produces a segmentation of customers based on their characteristics, enabling the creation of distinct profiles. Some of the results include:

- **Distributions by customer group**: Comparison of key feature distributions such as income, age, education, etc.
- **Cluster profiles**: Descriptive analysis of each cluster and its main characteristics.
- **Visualizations**: 2D and 3D plots to explore the clusters and the relationship between features.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and create a Pull Request with your changes. Please follow best coding practices and document any changes you make.

## License

This project is licensed under the Apache License 2.0. 


