# Mall Customer Segmentation with Hierarchical Clustering

This project demonstrates the application of **Hierarchical Clustering** to segment mall customers based on their spending behavior and annual income. It uses various data visualization techniques, including 2D scatter plots and 3D plots using **Plotly**, to visualize the clustering results.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Visualization](#visualization)
- [Technologies Used](#technologies-used)
- [License](#license)

## Project Overview

The goal of this project is to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**. We apply **Agglomerative Hierarchical Clustering** to form clusters of customers with similar spending behaviors and visualize the clusters in both 2D and 3D spaces.

## Dataset

The dataset used for this project is the **Mall Customers** dataset, which contains the following features:
- **CustomerID**: Unique identifier for each customer
- **Genre**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousand dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

You can download the dataset from [here](https://github.com/Eya-Laouini/Mall-Customer-Segmentation/blob/main/Mall_Customers.csv).

## Installation

Follow these steps to set up and run the project on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://https://github.com/Eya-Laouini/Mall-Customer-Segmentation
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Mall-Customer-Segmentation
    ```

3. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    ```

4. **Activate the virtual environment**:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

6. **Run the Jupyter Notebook**:
6.1. Execute the cells in sequence to preprocess the data, perform clustering, and visualize the results.
6.2. Visualize the dendrogram, 2D clusters, and 3D cluster plots as shown in the notebook.


## Visualization
**Dendrogram**
This dendrogram visualizes the customer hierarchy, showing how clusters are merged at different distances.


**2D Scatter Plot**
Clusters of mall customers based on Annual Income and Spending Score.


**3D Plot with Plotly**
This 3D plot shows the clusters based on Age, Annual Income, and Spending Score.


## Technologies Used
**Python**: Main programming language
**Pandas**: Data manipulation and analysis
**NumPy**: Numerical computations
**Matplotlib**: 2D plotting
**Seaborn**: Statistical data visualization
**Plotly**: 3D interactive visualizations
**Scikit-learn**: Machine learning algorithms for clustering
**Jupyter Notebook**: Interactive development environment


**You can further personalize this based on your preferences or specific repository needs!**
