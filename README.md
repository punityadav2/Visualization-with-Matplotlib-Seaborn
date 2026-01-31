# Visualization with Matplotlib & Seaborn

## Project Overview
This project demonstrates various data visualization techniques using Python's two most popular plotting libraries: **Matplotlib** and **Seaborn**. Through two Jupyter notebooks, we explore how to create insightful and aesthetically pleasing plots to analyze different types of data, ranging from simple line charts to complex statistical visualizations.

## Libraries Used
- **Matplotlib**: For foundational plotting capabilities.
- **Seaborn**: For high-level interface to drawing attractive and informative statistical graphics.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.

## Notebooks Analysis

### 1. `visualization_matplotlib.ipynb`
This notebook focuses on the core functionalities of Matplotlib, demonstrating how to build plots from scratch and customize them.

*   **Key Visualizations**:
    *   **Line Plot**: Visualizes trends over time or ordered categories.
    *   **Bar Plot**: Compares quantities across different groups.
    *   **Histogram**: Shows the distribution of a numerical variable.
    *   **Scatter Plots**: Displays relationships between two variables, highlighting clusters or correlations. Includes customization with colors based on categorical data (e.g., distinguishing data points by sex or smoker status).
    *   **Stack Plot**: Visualizes the contribution of different categories to a whole over time.
    *   **Customization**: Demonstrates adding titles, labels, legends, and adjusting colors and markers.

### 2. `visualization_seaborn.ipynb`
This notebook leverages Seaborn's capabilities to handle complex datasets like 'tips', 'anscombe', and 'flights'. It emphasizes statistical exploration and uncovering patterns.

*   **Key Visualizations**:
    *   **Data Exploration**: Inspection of data types and initial sample rows (`head()`) to understand dataset structure.
    *   **Relational Plots**:
        *   **Scatter Plots**: Enhanced scatter plots using `hue` to differentiate groups (e.g., relationship between 'Total Bill' and 'Tip', colored by 'Smoker' status).
        *   **Pairplot**: A matrix of scatter plots and histograms to visualize pairwise relationships across the entire dataset.
    *   **Categorical Distributions**:
        *   **Box Plot**: Summarizes distributions, showing medians, quartiles, and outliers (e.g., 'Total Bill' distribution by 'Day', separated by 'Smoker' status).
        *   **Boxen Plot**: Enhanced box plot for larger datasets, providing more detail on the distribution shape.
        *   **Violin Plot (via Catplot)**: Combines box plot and kernel density estimation to show the distribution density of the data (e.g., 'Total Bill' vs 'Day', colored by 'Time').
    *   **Regression Plots**:
        *   Visualizes linear relationships (e.g., 'Size' vs. 'Total Bill') with confidence intervals.
        *   Includes customization of axis ticks and labels.
        *   **Anscombe's Quartet**: Demonstrates the importance of visualization by showing datasets that have identical summary statistics but vastly different distributions.
    *   **Time Series / Trend Visualization**:
        *   **FacetGrid & Pointplot**: Analyzes the 'flights' dataset to show passenger trends over years, broken down by month.
        *   **Data Aggregation**: Aggregates passenger counts by year to visualize long-term growth patterns.
