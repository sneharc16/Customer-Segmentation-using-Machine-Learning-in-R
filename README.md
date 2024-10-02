Customer Segmentation using Machine Learning in R

This project is a graded final project submission for BAS-108 Programming with R, during my second semester of B.Tech in Electronics and Communication with AI at Indira Gandhi Delhi Technical University for Women, Delhi.

Table of Contents

Project Description
Installation
Usage
Features
Contributing
License
Contact
Project Description

The goal of this project is to perform customer segmentation using various machine learning techniques in R. Customer segmentation is crucial for businesses to understand their customer base and tailor marketing strategies accordingly.

Installation

Prerequisites

R (version 4.0 or higher)
RStudio (optional but recommended)
Jupyter Notebook
Steps

Clone the repository:
git clone https://github.com/sneharc16/Customer-Segmentation-using-Machine-Learning-in-R.git
cd Customer-Segmentation-using-Machine-Learning-in-R
Install required R packages:
install.packages(c("tidyverse", "cluster", "factoextra", "NbClust"))
Usage

Running the Jupyter Notebook

Open Jupyter Notebook:
jupyter notebook
Navigate to the project directory and open Customer_Segmentation.ipynb.
Example Commands

To perform K-means clustering:
kmeans_result <- kmeans(data, centers = 3)
To visualize clusters:
factoextra::fviz_cluster(kmeans_result, data)
Features

Data Preprocessing: Cleaning and preparing the dataset for analysis.
Clustering Algorithms: Implementation of K-means and Hierarchical clustering.
Visualization: Various plots to visualize the clusters and their characteristics.
Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

Sneha RC

GitHub Profile
Email
